# T-Pot Honeypot Report - 2026-10-26T11:54:59Z

Source data: `20261026T115007Z` &nbsp;|&nbsp; Total events analyzed: **465602** &nbsp;|&nbsp; Unique attacker IPs: **6626**

Events by source: `honeypots`: 52976, `suricata`: 346791, `p0f`: 65835

_232839 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `77.91.71.90` | 1817 | Israel | Tel Aviv | NEW |
| `45.148.10.9` | 1218 | The Netherlands | Amsterdam | Techoff SRV Limited |
| `77.239.124.36` | 1146 | France | Paris | RocketCloud |
| `135.148.217.213` | 1021 | United States | Warrenton | Cyera |
| `43.128.101.247` | 769 | Singapore | Singapore | Tencent Cloud Computing |
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
| `77.237.239.31` | 753 | France | Lauterbourg | Contabo GmbH |
| `45.198.224.124` | 655 | Sweden | Stockholm | Vpsvault.host LTD |
| `83.168.110.251` | 522 | Poland | Warsaw | SkyPass Solutions Sp. z.o.o |
| `190.119.63.81` | 501 | Peru | Lima | America Movil Peru S.A.C |
| `77.239.124.206` | 476 | France | Paris | RocketCloud |
| `91.92.47.87` | 443 | The Netherlands | Amsterdam | TechTies Inc |
| `165.154.137.186` | 389 | Vietnam | Ho Chi Minh City | Ucloud Information Technology (hk) Limited |
| `185.218.86.25` | 366 | Hong Kong | Sheung Wan | TC DATACENTER LIMITED |
| `137.23.38.53` | 321 | India | Mumbai | Oracle Cloud Infrastructure (ap-mumbai-1) |
| `94.154.43.250` | 320 | The Netherlands | Amsterdam | FOP Danik Vyacheslav Evgenievich |
| `109.160.32.123` | 263 | The Netherlands | Amsterdam | GBTCloud |

## Top Countries
| Country | Events |
|---|---:|
| United States | 15063 |
| Mauritius | 12734 |
| France | 7407 |
| The Netherlands | 6373 |
| China | 5250 |
| Israel | 2650 |
| Germany | 2640 |
| Singapore | 1817 |
| United Kingdom | 1121 |
| Hong Kong | 1072 |
| Belgium | 1015 |
| India | 943 |
| Sweden | 929 |
| Kazakhstan | 806 |
| Brazil | 615 |
| Canada | 610 |
| Poland | 595 |
| Thailand | 550 |
| Japan | 536 |
| Vietnam | 529 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 34451 |
| 80 | 21210 |
| 443 | 12822 |
| 64295 | 44 |
| 40692 | 7 |
| 38630 | 2 |
| 58218 | 2 |
| 51106 | 2 |
| 37928 | 2 |
| 60332 | 2 |
| 41128 | 2 |
| 42246 | 2 |
| 57058 | 2 |
| 42258 | 2 |
| 39950 | 2 |
| 55764 | 2 |
| 56322 | 2 |
| 40688 | 2 |
| 37174 | 2 |
| 33382 | 2 |

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
| `47.242.67.96` | 95 |
| `77.239.124.149` | 76 |
| `109.160.32.123` | 64 |
| `77.91.71.90` | 60 |
| `123.139.242.2` | 47 |
| `77.239.124.61` | 46 |
| `51.75.200.186` | 35 |
| `180.76.147.239` | 31 |
| `113.98.254.50` | 31 |
| `223.243.179.70` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 4

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 128 |
| `140.248.150.49` | 85 |
| `146.75.30.49` | 35 |
| `54.173.240.110` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 29 |
| `root` | `password` | 26 |
| `root` | `root` | 25 |
| `root` | `admin` | 24 |
| `root` | `passwd` | 19 |
| `root` | `ubuntu` | 17 |
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
| 2026-09-26 | 1807 |
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
| 2026-10-23 | 2357 |
| 2026-10-24 | 1794 |
| 2026-10-25 | 2210 |
| 2026-10-26 | 1793 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._