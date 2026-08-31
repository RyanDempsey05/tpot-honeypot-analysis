# T-Pot Honeypot Analysis

A T-Pot honeypot deployed on AWS EC2, paired with a Python pipeline that pulls its logs, parses them, geolocates and attributes the source addresses, and publishes a report every day through GitHub Actions.

The honeypot itself is upstream [T-Pot](https://github.com/telekom-security/tpotce) from Telekom Security. Everything in this repository (deployment, extraction, parsing, analysis, and the scheduled workflow) is mine. T-Pot produces logs; this code turns them into something readable.

## Architecture

**Sensor.** T-Pot (Mini flavor) on a `t3.medium` EC2 instance, Ubuntu, 32 GB disk, `us-east-1`. Ports 22, 80, and 443 are exposed as lures. The services listening there are imitations that log everything and grant nothing real. Management SSH runs on 64295.

**Pipeline.** `scripts/` connects over SSH, archives the T-Pot log directories, downloads and extracts them, parses the JSON-lines output, resolves each source IP to a country/city/ASN, applies brute-force and port-scan thresholds, and writes a Markdown report plus a metrics JSON.

| Script | Role |
|---|---|
| `deploy_tpot.py` | Provisions T-Pot on a fresh host |
| `extract_logs.py` | Archives and downloads remote logs |
| `analyze_logs.py` | Parses, aggregates, writes the report |
| `common/log_parsing.py` | Event loading, format normalisation, dedup |
| `common/config.py` | Config resolution, env-var merge |
| `generate_dashboard.py` | Chart-based HTML view of the same data |

**Automation.** `.github/workflows/honeypot-report.yml` runs the chain daily at 06:00 UTC and commits the output to `reports/`. No manual step.

## Findings

Figures are from the 2026-08-30 report, covering three weeks of continuous collection (2026-08-09 through 2026-08-30, plus an earlier partial capture on 2026-07-18).

**337,066 events, 5,190 unique attacker IPs**

By source: Suricata 258,284, p0f 43,344, honeypots 35,438. A further 181,823 events were excluded as allowlisted or private. Suricata and p0f observe all traffic crossing the host, including its own outbound connections and administrative access, so filtering those out is necessary to keep attacker metrics honest.

### Traffic shape

Web ports now lead: 80 draws 17,799 events, then 22 at 15,760 and 443 at 14,448. Earlier in the collection window SSH was ahead of both, so HTTP probing has grown faster than SSH brute-forcing over three weeks.

Port 64295, the non-standard management port, recorded 40 events. That is a small number but a useful one: moving SSH to a high port does not make it invisible, because scanners sweep there too.

Volume concentrates in the United States (19,023), China (4,392), the Netherlands (3,819), Sweden (2,084), and Singapore (2,052).

### Cloud infrastructure as the dominant platform

Eight of the twenty highest-volume sources are Google Cloud, spread across `us-west1`, `us-east4`, `europe-west4`, `asia-southeast1`, `us-west2`, and `us-east1`. The two heaviest sources overall are GCP addresses at 2,372 and 2,356 events. AWS (`eu-north-1`), Microsoft Azure (`westus3`), Tencent Cloud, OVH, and Akamai also appear near the top.

This is why the United States leads the country table by a factor of four. That figure reflects datacenter geography, not attacker geography, and reading it as the latter would be a mistake.

Three consecutive addresses in one `/24` (`34.34.225.111`, `.145`, `.169`) contributed 2,353 events between them, all Google Cloud `us-east1`.

### Brute-force activity

Twenty sources crossed the >= 5 authentication-attempt threshold. The most persistent:

| IP | Auth attempts | Origin |
|---|---:|---|
| `91.92.40.36` | 425 | Amsterdam, NL (TechTies) |
| `220.168.118.133` | 368 | Changsha, CN |
| `51.75.200.186` | 248 | Roubaix, FR (OVH) |
| `160.187.174.22` | 247 | Deli Serdang, ID |
| `106.75.216.134` | 223 | Yangpu, CN (UCloud) |

Counting per IP understates the most persistent operator here. `91.92.40.36` (425), `91.92.40.23` (80), and `91.92.40.153` (76) share a `/24` and a provider, totalling 581 attempts. Ranked individually, two of the three look like minor sources; grouped by subnet they are the single most active brute-force origin in the dataset. Subnet and ASN aggregation is the obvious next improvement to the analysis.

Three sources crossed the port-scan threshold, the heaviest touching 71 distinct ports. Two of those three (`146.75.38.49` and `146.75.30.49`) again share upstream address space.

### Credential patterns

The credential distribution is extremely flat. Direct inspection of the raw logs during an earlier window found roughly 1,780 attempts, of which the twenty most common passwords accounted for about 377, meaning some 80% of attempts used passwords tried fewer than a dozen times each. This is dictionary spraying rather than repetition of a short list.

The most frequent pairs are the expected ones: `root/root` (30), `root/123456` (28), `root/admin` (26), `root/qwerty` (19). Alongside those, a distinct category persists:

`root/debian` (19), `root/ubuntu` (15), `root/linux` (15), `root/mysql` (14), `root/apache` (14), `root/centos` (13), `root/vps` (13), `root/host` (13), `root/www` (13)

These are distribution names, service names, and hosting terms used as passwords. The bots are wagering that the operator reused the OS or a running service as a credential. That is a different heuristic from numeric-string spraying, and it suggests wordlists assembled from observed real-world defaults rather than generic breach dumps.

Note that the report's credential table counts username/password *pairs*. Counting passwords irrespective of username gives different figures, since a common password is split across many usernames. The two views answer different questions and are not directly comparable.

### Research scanners in the data

Not everything reaching the honeypot is hostile. Censys and the Shadowserver Foundation both appear in the attacker tables. Both are organisations that scan the internet to catalogue exposed hosts and notify network owners, and Censys in particular surfaces across several distinct addresses. Any honest reading of honeypot data has to separate this from genuine attack traffic, since counting it as hostile inflates the numbers.

No malware families were matched via Suricata signatures during this period.

## Limitations

The sensor runs T-Pot's **Mini** flavor, chosen to fit within 4 GB of RAM. Port 22 is served by the generic `honeypots` container rather than Cowrie, which means the sensor records authentication attempts and their outcome but does not emulate a shell session afterward.

Concretely: when a fake login is granted, no post-compromise behaviour is captured. There are no session transcripts and no malware samples, and `cowrie/downloads/` is empty by design rather than by accident. Running the Standard flavor on a larger instance would capture command histories and any payloads pulled down, which is the more valuable half of honeypot data.

Attacker metrics are aggregated per IP address. As the brute-force section shows, this understates operators who distribute across a subnet.

Geolocation and ASN attribution come from a free keyless API and are indicative rather than authoritative. See `docs/METHODOLOGY.md` for caveats on the Suricata signature matching.

## Debugging notes

The first automated reports claimed **16 events and 0 unique attacker IPs**. Direct inspection of the box contradicted that: the raw logs held 32 SSH attempts and 294 HTTP requests for the same window.

Tracing it layer by layer:

* **Extraction was fine.** `extract_logs.py` archives whole service directories over SSH, so the rotated files were being downloaded correctly.
* **Parsing was not.** `load_events` and `dump_sample` globbed for `*.log` and `*.json` only. T-Pot rotates and compresses logs to names like `ssh.log.1.gz`, which match neither pattern. Those files were never opened. Not skipped, not logged as errors, simply never matched by the glob. The pipeline reported zero with complete confidence.

The fix was three parts: add `*.log.*` and `*.json.*` to the glob patterns; branch on the `.gz` suffix to open compressed files with `gzip.open(..., "rt")`; and deduplicate on `(src_ip, timestamp)` so that re-reading historical rotations on each run does not inflate counts. Dedup applies only to events carrying a `src_ip`, since flow records without one would otherwise collide falsely on `(None, timestamp)`.

Verification was against numbers derived by hand from the raw logs before the fix: 11 unique SSH source IPs, two HTTP sources tied at the top. The corrected pipeline reproduced them exactly. Event volume went from 16 to 6,747 on the same input.

A second, smaller issue came from the same family. `config.yaml` is gitignored, so ignore-list edits that worked locally never reached the Actions runner, and the operator's own address kept appearing as a top attacker in automated reports. Resolved by merging a `TPOT_IGNORE_IPS` repository variable with the file-based list rather than letting either silently override the other.

## Setup

**Requirements:** Python 3.11+, an EC2 host running T-Pot, SSH key access on port 64295.

```bash
pip install -r requirements.txt
cp config/config.example.yaml config/config.yaml
# edit config.yaml: host, ssh_key_path, tpot user
python scripts/extract_logs.py     # pull a log snapshot
python scripts/analyze_logs.py     # parse and write the report
```

`config/config.yaml` is gitignored. It holds host and key paths and never reaches CI.

**For the scheduled workflow**, set in repository settings:

| Type | Name | Purpose |
|---|---|---|
| Secret | `EC2_SSH_PRIVATE_KEY` | Management SSH key |
| Variable | `TPOT_EC2_HOST` | Public address of the sensor |
| Variable | `TPOT_USER` | SSH user |
| Variable | `TPOT_IGNORE_IPS` | Comma-separated addresses to exclude from attacker metrics |

`TPOT_IGNORE_IPS` merges with `analysis.ignore_ips` from `config.yaml`, so local and CI runs can each hold entries the other does not.

**Note on hosts without an Elastic IP:** stopping and starting the instance assigns a new public address, invalidating both `config.yaml` and `TPOT_EC2_HOST`. Attach an Elastic IP if the sensor will be cycled on and off.

## Reports

`reports/LATEST.md` always holds the most recent run. Dated reports accumulate alongside it, with machine-readable metrics under `reports/data/`.
