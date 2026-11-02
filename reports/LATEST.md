# T-Pot Honeypot Report - 2026-11-02T14:13:54Z

Source data: `20261102T140910Z` &nbsp;|&nbsp; Total events analyzed: **548241** &nbsp;|&nbsp; Unique attacker IPs: **6386**

Events by source: `honeypots`: 51127, `suricata`: 415588, `p0f`: 81526

_234540 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `45.141.202.113` | 4496 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `77.91.71.90` | 2084 | Israel | Tel Aviv | NEW |
| `77.237.239.31` | 1375 | France | Lauterbourg | Contabo GmbH |
| `77.239.124.36` | 1146 | France | Paris | RocketCloud |
| `135.148.217.213` | 1021 | United States | New York | Cyera |
| `43.128.101.247` | 769 | Singapore | Singapore | Tencent Cloud Computing |
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
| `45.198.224.124` | 655 | Sweden | Stockholm | Vpsvault.host LTD |
| `47.113.193.48` | 591 | China | Shenzhen | Aliyun Computing Co., LTD |
| `138.226.239.91` | 527 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `138.226.239.90` | 527 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `83.168.110.251` | 522 | Poland | Warsaw | SkyPass Solutions Sp. z.o.o |
| `77.91.71.92` | 501 | Israel | Tel Aviv | NEW |
| `77.91.71.91` | 501 | Israel | Tel Aviv | NEW |
| `185.136.15.82` | 466 | Kazakhstan | Almaty | Vlad Cojuhari |
| `185.136.15.111` | 465 | Kazakhstan | Almaty | Vlad Cojuhari |
| `185.136.15.110` | 463 | Kazakhstan | Almaty | Vlad Cojuhari |

## Top Countries
| Country | Events |
|---|---:|
| United States | 15782 |
| Mauritius | 12732 |
| The Netherlands | 9988 |
| France | 7179 |
| China | 6153 |
| Israel | 4510 |
| Germany | 2632 |
| Kazakhstan | 2401 |
| Singapore | 1520 |
| United Kingdom | 992 |
| Sweden | 940 |
| Poland | 888 |
| Hong Kong | 880 |
| Belgium | 741 |
| India | 726 |
| Japan | 671 |
| Thailand | 552 |
| Canada | 523 |
| Hungary | 515 |
| Brazil | 501 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 38019 |
| 80 | 26265 |
| 443 | 10975 |
| 64295 | 47 |
| 40692 | 7 |
| 57642 | 2 |
| 51106 | 2 |
| 55764 | 2 |
| 36980 | 2 |
| 58218 | 2 |
| 40688 | 2 |
| 37174 | 2 |
| 38630 | 2 |
| 36572 | 2 |
| 58618 | 2 |
| 33382 | 2 |
| 43596 | 2 |
| 58424 | 2 |
| 39950 | 2 |
| 60332 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `196.20.216.206` | 5778 |
| `106.38.51.68` | 1286 |
| `77.239.124.36` | 513 |
| `135.148.217.213` | 499 |
| `43.128.101.247` | 381 |
| `47.113.193.48` | 266 |
| `83.168.110.251` | 253 |
| `47.251.165.65` | 151 |
| `91.218.108.6` | 104 |
| `77.91.71.90` | 70 |
| `109.160.32.123` | 64 |
| `123.139.242.2` | 47 |
| `77.239.124.61` | 46 |
| `103.72.57.129` | 45 |
| `4.4.66.84` | 31 |
| `113.98.254.50` | 31 |
| `154.211.13.102` | 31 |
| `42.101.60.58` | 31 |
| `120.71.148.144` | 31 |
| `121.227.31.82` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 6

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 93 |
| `140.248.150.49` | 74 |
| `146.75.30.49` | 30 |
| `54.224.99.219` | 6 |
| `67.202.15.124` | 6 |
| `54.173.240.110` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 27 |
| `root` | `password` | 22 |
| `root` | `root` | 22 |
| `root` | `admin` | 21 |
| `root` | `passwd` | 20 |
| `root` | `ubuntu` | 20 |
| `root` | `qwerty` | 19 |
| `root` | `linux` | 19 |
| `root` | `guest` | 19 |
| `root` | `apache` | 18 |
| `root` | `pass` | 18 |
| `root` | `temp` | 18 |
| `root` | `system` | 18 |
| `root` | `sys` | 18 |
| `root` | `sysadmin` | 18 |
| `root` | `super` | 18 |
| `root` | `centos` | 17 |
| `root` | `nginx` | 17 |
| `root` | `mysql` | 17 |
| `root` | `docker` | 17 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-03 | 901 |
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
| 2026-10-31 | 1728 |
| 2026-11-01 | 2953 |
| 2026-11-02 | 1844 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._