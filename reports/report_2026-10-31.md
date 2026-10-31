# T-Pot Honeypot Report - 2026-10-31T11:28:45Z

Source data: `20261031T112359Z` &nbsp;|&nbsp; Total events analyzed: **498519** &nbsp;|&nbsp; Unique attacker IPs: **6543**

Events by source: `honeypots`: 51428, `suricata`: 369148, `p0f`: 77943

_233341 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `45.141.202.113` | 4326 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `77.91.71.90` | 2047 | Israel | Tel Aviv | NEW |
| `77.237.239.31` | 1375 | France | Lauterbourg | Contabo GmbH |
| `77.239.124.36` | 1146 | France | Paris | RocketCloud |
| `135.148.217.213` | 1021 | United States | Warrenton | Cyera |
| `43.128.101.247` | 769 | Singapore | Singapore | Tencent Cloud Computing |
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
| `45.198.224.124` | 655 | Sweden | Stockholm | Vpsvault.host LTD |
| `83.168.110.251` | 522 | Poland | Warsaw | SkyPass Solutions Sp. z.o.o |
| `77.239.124.206` | 476 | France | Paris | RocketCloud |
| `91.92.47.87` | 443 | The Netherlands | Amsterdam | TechTies Inc |
| `138.226.239.90` | 433 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `138.226.239.91` | 433 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `77.91.71.92` | 405 | Israel | Tel Aviv | NEW |
| `77.91.71.91` | 405 | Israel | Tel Aviv | NEW |
| `165.154.137.186` | 389 | Vietnam | Ho Chi Minh City | Ucloud Information Technology (hk) Limited |
| `185.136.15.82` | 370 | Kazakhstan | Almaty | Vlad Cojuhari |

## Top Countries
| Country | Events |
|---|---:|
| United States | 15366 |
| Mauritius | 12734 |
| The Netherlands | 9921 |
| France | 7790 |
| China | 5349 |
| Israel | 4005 |
| Germany | 2719 |
| Kazakhstan | 1923 |
| Singapore | 1584 |
| United Kingdom | 999 |
| Sweden | 950 |
| India | 888 |
| Belgium | 884 |
| Hong Kong | 755 |
| Japan | 702 |
| Poland | 628 |
| Vietnam | 592 |
| Thailand | 557 |
| Bulgaria | 530 |
| Canada | 529 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 36603 |
| 80 | 26429 |
| 443 | 11075 |
| 64295 | 46 |
| 40692 | 7 |
| 36572 | 2 |
| 40688 | 2 |
| 37174 | 2 |
| 38630 | 2 |
| 33382 | 2 |
| 55764 | 2 |
| 43596 | 2 |
| 42258 | 2 |
| 45508 | 2 |
| 36366 | 2 |
| 51254 | 2 |
| 60890 | 2 |
| 39950 | 2 |
| 58218 | 2 |
| 35072 | 2 |

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
| `165.154.137.186` | 185 |
| `77.239.124.206` | 179 |
| `91.218.108.6` | 104 |
| `77.91.71.90` | 68 |
| `109.160.32.123` | 64 |
| `123.139.242.2` | 47 |
| `77.239.124.61` | 46 |
| `103.72.57.129` | 45 |
| `51.75.200.186` | 35 |
| `154.211.13.102` | 31 |
| `42.101.60.58` | 31 |
| `223.243.179.70` | 31 |
| `60.165.119.59` | 31 |
| `113.98.254.50` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 6

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 95 |
| `140.248.150.49` | 70 |
| `146.75.30.49` | 32 |
| `67.202.15.124` | 6 |
| `54.224.99.219` | 5 |
| `54.173.240.110` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 27 |
| `root` | `password` | 23 |
| `root` | `root` | 23 |
| `root` | `admin` | 22 |
| `root` | `ubuntu` | 20 |
| `root` | `passwd` | 20 |
| `root` | `apache` | 19 |
| `root` | `linux` | 19 |
| `root` | `guest` | 19 |
| `root` | `vps` | 18 |
| `root` | `default` | 18 |
| `root` | `pass` | 18 |
| `root` | `temp` | 18 |
| `root` | `system` | 18 |
| `root` | `sys` | 18 |
| `root` | `sysadmin` | 18 |
| `root` | `super` | 18 |
| `root` | `qwerty` | 18 |
| `root` | `web` | 17 |
| `root` | `centos` | 17 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-01 | 1666 |
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
| 2026-10-23 | 2357 |
| 2026-10-24 | 1794 |
| 2026-10-25 | 2210 |
| 2026-10-26 | 2735 |
| 2026-10-27 | 1735 |
| 2026-10-28 | 6846 |
| 2026-10-29 | 1567 |
| 2026-10-30 | 1709 |
| 2026-10-31 | 996 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._