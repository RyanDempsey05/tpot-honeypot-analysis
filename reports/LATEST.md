# T-Pot Honeypot Report - 2026-10-20T10:41:38Z

Source data: `20261020T103650Z` &nbsp;|&nbsp; Total events analyzed: **453691** &nbsp;|&nbsp; Unique attacker IPs: **6698**

Events by source: `honeypots`: 54081, `suricata`: 338315, `p0f`: 61295

_230977 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `77.91.71.90` | 1642 | Israel | Tel Aviv | NEW |
| `45.148.10.9` | 1218 | The Netherlands | Amsterdam | Techoff SRV Limited |
| `77.239.124.36` | 1146 | France | Paris | RocketCloud |
| `135.148.217.213` | 1021 | United States | Warrenton | Cyera |
| `190.119.63.81` | 1008 | Peru | Lima | America Movil Peru S.A.C |
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
| `74.207.252.24` | 690 | United States | Fremont | Linode |
| `45.198.224.124` | 634 | Sweden | Stockholm | Vpsvault.host LTD |
| `185.218.86.25` | 548 | Hong Kong | Sheung Wan | TC DATACENTER LIMITED |
| `83.168.110.251` | 522 | Poland | Warsaw | SkyPass Solutions Sp. z.o.o |
| `77.239.124.206` | 476 | France | Paris | RocketCloud |
| `91.92.47.87` | 443 | The Netherlands | Amsterdam | TechTies Inc |
| `165.154.137.186` | 389 | Vietnam | Ho Chi Minh City | Ucloud Information Technology (hk) Limited |
| `137.23.38.53` | 321 | India | Mumbai | Oracle Cloud Infrastructure (ap-mumbai-1) |
| `94.154.43.250` | 320 | The Netherlands | Amsterdam | FOP Danik Vyacheslav Evgenievich |
| `35.230.81.28` | 257 | United States | The Dalles | Google Cloud (us-west1) |
| `34.193.125.14` | 256 | United States | Ashburn | AWS EC2 (us-east-1) |

## Top Countries
| Country | Events |
|---|---:|
| United States | 15908 |
| Mauritius | 12734 |
| France | 6773 |
| The Netherlands | 5463 |
| China | 4929 |
| Germany | 2756 |
| United Kingdom | 1881 |
| Israel | 1722 |
| Hong Kong | 1366 |
| Belgium | 1306 |
| Singapore | 1137 |
| Sweden | 1013 |
| Peru | 1009 |
| Canada | 863 |
| Brazil | 721 |
| India | 699 |
| Poland | 602 |
| Thailand | 552 |
| Vietnam | 519 |
| Japan | 490 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 32001 |
| 80 | 20803 |
| 443 | 14126 |
| 64295 | 39 |
| 40692 | 7 |
| 50296 | 7 |
| 58618 | 2 |
| 57058 | 2 |
| 35072 | 2 |
| 33382 | 2 |
| 58218 | 2 |
| 39950 | 2 |
| 55072 | 2 |
| 36366 | 2 |
| 49914 | 2 |
| 42258 | 2 |
| 60842 | 2 |
| 55764 | 2 |
| 33634 | 2 |
| 47132 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `196.20.216.206` | 5778 |
| `106.38.51.68` | 1286 |
| `77.239.124.36` | 513 |
| `135.148.217.213` | 499 |
| `190.119.63.81` | 496 |
| `83.168.110.251` | 253 |
| `165.154.137.186` | 185 |
| `77.239.124.206` | 179 |
| `91.218.108.6` | 104 |
| `47.251.70.129` | 100 |
| `47.242.67.96` | 95 |
| `39.106.217.151` | 94 |
| `50.6.227.30` | 80 |
| `77.239.124.149` | 76 |
| `77.91.71.90` | 55 |
| `123.139.242.2` | 47 |
| `77.239.124.61` | 46 |
| `51.75.200.186` | 35 |
| `103.243.25.44` | 31 |
| `41.225.238.233` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 5

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 107 |
| `140.248.150.49` | 64 |
| `146.75.30.49` | 31 |
| `54.224.99.219` | 5 |
| `100.25.103.9` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 31 |
| `root` | `root` | 26 |
| `root` | `password` | 25 |
| `root` | `admin` | 24 |
| `root` | `passwd` | 18 |
| `root` | `guest` | 17 |
| `root` | `pass` | 16 |
| `root` | `qwerty` | 16 |
| `root` | `default` | 15 |
| `root` | `temp` | 15 |
| `root` | `system` | 15 |
| `root` | `sys` | 15 |
| `root` | `sysadmin` | 15 |
| `root` | `super` | 15 |
| `root` | `ubuntu` | 15 |
| `root` | `linux` | 14 |
| `root` | `vps` | 14 |
| `root` | `administrator` | 14 |
| `root` | `portfolio` | 14 |
| `root` | `temponly` | 14 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-09-20 | 2363 |
| 2026-09-21 | 1441 |
| 2026-09-22 | 1172 |
| 2026-09-23 | 2039 |
| 2026-09-24 | 1080 |
| 2026-09-25 | 1743 |
| 2026-09-26 | 2297 |
| 2026-09-27 | 1152 |
| 2026-09-28 | 1385 |
| 2026-09-29 | 1049 |
| 2026-09-30 | 2514 |
| 2026-10-01 | 1943 |
| 2026-10-02 | 2227 |
| 2026-10-03 | 1388 |
| 2026-10-04 | 1132 |
| 2026-10-05 | 1532 |
| 2026-10-06 | 1391 |
| 2026-10-07 | 6194 |
| 2026-10-08 | 1248 |
| 2026-10-09 | 4361 |
| 2026-10-10 | 14015 |
| 2026-10-11 | 1189 |
| 2026-10-12 | 2661 |
| 2026-10-13 | 1690 |
| 2026-10-14 | 1412 |
| 2026-10-15 | 1146 |
| 2026-10-16 | 1221 |
| 2026-10-17 | 1851 |
| 2026-10-18 | 1028 |
| 2026-10-19 | 1172 |
| 2026-10-20 | 377 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._