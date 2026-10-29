# T-Pot Honeypot Report - 2026-10-29T12:01:40Z

Source data: `20261029T115658Z` &nbsp;|&nbsp; Total events analyzed: **498786** &nbsp;|&nbsp; Unique attacker IPs: **6575**

Events by source: `honeypots`: 55204, `suricata`: 366708, `p0f`: 76874

_235716 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `45.141.202.113` | 4326 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `77.91.71.90` | 1957 | Israel | Tel Aviv | NEW |
| `77.237.239.31` | 1375 | France | Lauterbourg | Contabo GmbH |
| `45.148.10.9` | 1218 | The Netherlands | Amsterdam | Techoff SRV Limited |
| `77.239.124.36` | 1146 | France | Paris | RocketCloud |
| `135.148.217.213` | 1021 | United States | Warrenton | Cyera |
| `43.128.101.247` | 769 | Singapore | Singapore | Tencent Cloud Computing |
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
| `45.198.224.124` | 655 | Sweden | Stockholm | Vpsvault.host LTD |
| `83.168.110.251` | 522 | Poland | Warsaw | SkyPass Solutions Sp. z.o.o |
| `77.239.124.206` | 476 | France | Paris | RocketCloud |
| `91.92.47.87` | 443 | The Netherlands | Amsterdam | TechTies Inc |
| `165.154.137.186` | 389 | Vietnam | Ho Chi Minh City | Ucloud Information Technology (hk) Limited |
| `138.226.239.91` | 347 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `138.226.239.90` | 341 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `137.23.38.53` | 321 | India | Mumbai | Oracle Cloud Infrastructure (ap-mumbai-1) |
| `94.154.43.250` | 320 | The Netherlands | Amsterdam | FOP Danik Vyacheslav Evgenievich |

## Top Countries
| Country | Events |
|---|---:|
| United States | 15141 |
| Mauritius | 12734 |
| The Netherlands | 11011 |
| France | 7785 |
| China | 5388 |
| Israel | 3462 |
| Germany | 2740 |
| Singapore | 1705 |
| Kazakhstan | 1480 |
| United Kingdom | 1031 |
| Belgium | 978 |
| Sweden | 950 |
| India | 928 |
| Hong Kong | 821 |
| Vietnam | 626 |
| Poland | 626 |
| Thailand | 552 |
| Brazil | 549 |
| Canada | 547 |
| Japan | 530 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 35572 |
| 80 | 26266 |
| 443 | 12510 |
| 64295 | 45 |
| 40692 | 7 |
| 36366 | 2 |
| 45508 | 2 |
| 42258 | 2 |
| 43596 | 2 |
| 39950 | 2 |
| 40688 | 2 |
| 37174 | 2 |
| 58218 | 2 |
| 53388 | 2 |
| 51254 | 2 |
| 58424 | 2 |
| 56322 | 2 |
| 60332 | 2 |
| 41128 | 2 |
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
| `77.91.71.90` | 65 |
| `109.160.32.123` | 64 |
| `123.139.242.2` | 47 |
| `77.239.124.61` | 46 |
| `103.72.57.129` | 45 |
| `51.75.200.186` | 35 |
| `49.12.249.111` | 31 |
| `213.215.209.101` | 31 |
| `121.227.31.82` | 31 |
| `103.243.25.44` | 31 |
| `180.76.147.239` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 6

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 97 |
| `140.248.150.49` | 70 |
| `146.75.30.49` | 30 |
| `54.173.240.110` | 6 |
| `67.202.15.124` | 5 |
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
| `root` | `passwd` | 21 |
| `root` | `ubuntu` | 20 |
| `root` | `guest` | 20 |
| `root` | `linux` | 19 |
| `root` | `vps` | 19 |
| `root` | `default` | 19 |
| `root` | `pass` | 19 |
| `root` | `temp` | 19 |
| `root` | `system` | 19 |
| `root` | `sys` | 19 |
| `root` | `sysadmin` | 19 |
| `root` | `super` | 19 |
| `root` | `qwerty` | 19 |
| `root` | `apache` | 18 |
| `root` | `host` | 18 |
| `root` | `administrator` | 18 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-09-29 | 898 |
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
| 2026-10-26 | 2735 |
| 2026-10-27 | 1735 |
| 2026-10-28 | 6846 |
| 2026-10-29 | 826 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._