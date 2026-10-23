# T-Pot Honeypot Report - 2026-10-23T10:46:18Z

Source data: `20261023T104125Z` &nbsp;|&nbsp; Total events analyzed: **456438** &nbsp;|&nbsp; Unique attacker IPs: **6710**

Events by source: `honeypots`: 52998, `suricata`: 339960, `p0f`: 63480

_231470 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `77.91.71.90` | 1677 | Israel | Tel Aviv | NEW |
| `45.148.10.9` | 1218 | The Netherlands | Amsterdam | Techoff SRV Limited |
| `77.239.124.36` | 1146 | France | Paris | RocketCloud |
| `135.148.217.213` | 1021 | United States | Warrenton | Cyera |
| `43.128.101.247` | 769 | Singapore | Singapore | Tencent Cloud Computing |
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
| `45.198.224.124` | 655 | Sweden | Stockholm | Vpsvault.host LTD |
| `83.168.110.251` | 522 | Poland | Warsaw | SkyPass Solutions Sp. z.o.o |
| `190.119.63.81` | 501 | Peru | Lima | America Movil Peru S.A.C |
| `77.239.124.206` | 476 | France | Paris | RocketCloud |
| `185.218.86.25` | 453 | Hong Kong | Sheung Wan | TC DATACENTER LIMITED |
| `91.92.47.87` | 443 | The Netherlands | Amsterdam | TechTies Inc |
| `165.154.137.186` | 389 | Vietnam | Ho Chi Minh City | Ucloud Information Technology (hk) Limited |
| `137.23.38.53` | 321 | India | Mumbai | Oracle Cloud Infrastructure (ap-mumbai-1) |
| `94.154.43.250` | 320 | The Netherlands | Amsterdam | FOP Danik Vyacheslav Evgenievich |
| `109.160.32.123` | 263 | The Netherlands | Amsterdam | GBTCloud |
| `35.230.81.28` | 257 | United States | The Dalles | Google Cloud (us-west1) |

## Top Countries
| Country | Events |
|---|---:|
| United States | 14947 |
| Mauritius | 12734 |
| France | 6661 |
| The Netherlands | 5911 |
| China | 4740 |
| Germany | 2726 |
| Singapore | 2008 |
| United Kingdom | 1869 |
| Israel | 1851 |
| Belgium | 1166 |
| Hong Kong | 1153 |
| Sweden | 956 |
| India | 953 |
| Canada | 843 |
| Brazil | 665 |
| Poland | 591 |
| Thailand | 550 |
| Japan | 550 |
| Vietnam | 533 |
| Peru | 502 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 32869 |
| 80 | 20007 |
| 443 | 13662 |
| 64295 | 39 |
| 50296 | 7 |
| 40692 | 7 |
| 57058 | 2 |
| 53388 | 2 |
| 56322 | 2 |
| 35072 | 2 |
| 43596 | 2 |
| 55072 | 2 |
| 42258 | 2 |
| 60890 | 2 |
| 60332 | 2 |
| 41128 | 2 |
| 37928 | 2 |
| 55764 | 2 |
| 58618 | 2 |
| 51106 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `196.20.216.206` | 5778 |
| `106.38.51.68` | 1286 |
| `77.239.124.36` | 513 |
| `135.148.217.213` | 499 |
| `43.128.101.247` | 381 |
| `83.168.110.251` | 253 |
| `190.119.63.81` | 248 |
| `165.154.137.186` | 185 |
| `77.239.124.206` | 179 |
| `91.218.108.6` | 104 |
| `47.251.70.129` | 100 |
| `47.242.67.96` | 95 |
| `50.6.227.30` | 80 |
| `77.239.124.149` | 76 |
| `109.160.32.123` | 64 |
| `77.91.71.90` | 57 |
| `123.139.242.2` | 47 |
| `77.239.124.61` | 46 |
| `51.75.200.186` | 35 |
| `180.76.147.239` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 4

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 108 |
| `140.248.150.49` | 56 |
| `146.75.30.49` | 28 |
| `54.224.99.219` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 30 |
| `root` | `password` | 26 |
| `root` | `root` | 25 |
| `root` | `admin` | 24 |
| `root` | `passwd` | 19 |
| `root` | `ubuntu` | 18 |
| `root` | `pass` | 17 |
| `root` | `guest` | 17 |
| `root` | `qwerty` | 17 |
| `root` | `linux` | 16 |
| `root` | `vps` | 16 |
| `root` | `default` | 16 |
| `root` | `temp` | 16 |
| `root` | `system` | 16 |
| `root` | `sys` | 16 |
| `root` | `sysadmin` | 16 |
| `root` | `super` | 16 |
| `root` | `apache` | 15 |
| `root` | `host` | 15 |
| `root` | `administrator` | 15 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-09-23 | 1808 |
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
| 2026-10-20 | 1022 |
| 2026-10-21 | 1233 |
| 2026-10-22 | 1869 |
| 2026-10-23 | 1054 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._