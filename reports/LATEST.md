# T-Pot Honeypot Report - 2026-11-20T14:38:48Z

Source data: `20261120T143430Z` &nbsp;|&nbsp; Total events analyzed: **674773** &nbsp;|&nbsp; Unique attacker IPs: **5854**

Events by source: `honeypots`: 68197, `suricata`: 518525, `p0f`: 88051

_226367 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `78.107.31.154` | 40881 | Russia | Tula | OOO Gala-Centr MSK |
| `45.141.202.113` | 16854 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `80.91.71.147` | 2282 | Türkiye | Istanbul | Hostlayici Internet ve Bilisim Hizmetleri |
| `109.160.32.171` | 1474 | The Netherlands | Amsterdam | GBTCloud |
| `77.237.239.31` | 1375 | France | Lauterbourg | Contabo GmbH |
| `83.168.110.67` | 616 | Poland | Warsaw | SkillHost |
| `77.91.71.90` | 613 | Israel | Tel Aviv | NEW |
| `77.91.71.91` | 609 | Israel | Tel Aviv | NEW |
| `138.226.239.91` | 599 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `47.113.193.48` | 592 | China | Shenzhen | Aliyun Computing Co., LTD |
| `77.91.71.24` | 583 | Israel | Tel Aviv | NEW |
| `185.136.15.111` | 575 | Kazakhstan | Almaty | Vlad Cojuhari |
| `77.91.71.92` | 574 | Israel | Tel Aviv | NEW |
| `77.91.71.25` | 572 | Israel | Tel Aviv | NEW |
| `77.91.71.23` | 571 | Israel | Tel Aviv | NEW |
| `185.136.15.82` | 570 | Kazakhstan | Almaty | Vlad Cojuhari |
| `138.226.239.90` | 569 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `185.136.15.110` | 567 | Kazakhstan | Almaty | Vlad Cojuhari |
| `185.136.15.81` | 566 | Kazakhstan | Almaty | Vlad Cojuhari |
| `185.136.15.80` | 563 | Kazakhstan | Almaty | Vlad Cojuhari |

## Top Countries
| Country | Events |
|---|---:|
| Russia | 41000 |
| The Netherlands | 23815 |
| United States | 15150 |
| China | 3687 |
| Israel | 3574 |
| Kazakhstan | 2942 |
| France | 2905 |
| Germany | 2509 |
| Türkiye | 2357 |
| Hong Kong | 1208 |
| Poland | 1002 |
| United Kingdom | 752 |
| Hungary | 635 |
| Singapore | 550 |
| Belgium | 508 |
| Japan | 473 |
| Indonesia | 472 |
| Brazil | 452 |
| India | 428 |
| Vietnam | 399 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 61935 |
| 443 | 23671 |
| 80 | 22771 |
| 64295 | 51 |
| 37208 | 7 |
| 60196 | 7 |
| 43412 | 3 |
| 56830 | 2 |
| 34048 | 2 |
| 39992 | 2 |
| 42024 | 2 |
| 54810 | 2 |
| 39950 | 2 |
| 45554 | 2 |
| 58978 | 2 |
| 48486 | 2 |
| 39100 | 2 |
| 36366 | 2 |
| 48596 | 2 |
| 36572 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `78.107.31.154` | 20093 |
| `109.160.32.171` | 679 |
| `83.168.110.67` | 301 |
| `47.113.193.48` | 266 |
| `125.39.11.27` | 159 |
| `47.251.165.65` | 151 |
| `180.76.228.8` | 134 |
| `210.195.210.116` | 105 |
| `118.70.239.231` | 62 |
| `103.72.57.129` | 45 |
| `8.217.68.84` | 32 |
| `121.227.31.82` | 31 |
| `4.4.66.84` | 31 |
| `94.204.5.49` | 31 |
| `120.71.148.144` | 31 |
| `50.114.172.201` | 31 |
| `223.243.179.70` | 31 |
| `42.236.73.142` | 31 |
| `60.165.119.59` | 31 |
| `101.47.28.226` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 12

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 55 |
| `140.248.150.49` | 55 |
| `146.75.30.49` | 29 |
| `185.125.188.59` | 9 |
| `185.125.188.54` | 9 |
| `185.125.188.57` | 9 |
| `185.125.188.55` | 9 |
| `67.202.15.124` | 8 |
| `185.125.188.60` | 8 |
| `185.125.188.58` | 8 |
| `54.234.187.186` | 6 |
| `54.224.99.219` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 26 |
| `root` | `admin` | 19 |
| `root` | `root` | 17 |
| `root` | `qwerty` | 17 |
| `root` | `ubuntu` | 16 |
| `root` | `passwd` | 16 |
| `root` | `guest` | 15 |
| `root` | `linux` | 14 |
| `root` | `apache` | 14 |
| `root` | `web` | 14 |
| `root` | `password` | 14 |
| `root` | `pass` | 14 |
| `root` | `temp` | 14 |
| `root` | `test` | 14 |
| `root` | `debian` | 13 |
| `root` | `centos` | 13 |
| `root` | `nginx` | 13 |
| `root` | `mysql` | 13 |
| `root` | `docker` | 13 |
| `root` | `vps` | 13 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-22 | 830 |
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
| 2026-11-02 | 2422 |
| 2026-11-03 | 11059 |
| 2026-11-04 | 8043 |
| 2026-11-05 | 1280 |
| 2026-11-06 | 2394 |
| 2026-11-07 | 817 |
| 2026-11-08 | 1147 |
| 2026-11-09 | 890 |
| 2026-11-10 | 1305 |
| 2026-11-11 | 31780 |
| 2026-11-12 | 12077 |
| 2026-11-13 | 1521 |
| 2026-11-14 | 1481 |
| 2026-11-15 | 1376 |
| 2026-11-16 | 991 |
| 2026-11-17 | 1061 |
| 2026-11-18 | 884 |
| 2026-11-19 | 1166 |
| 2026-11-20 | 678 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._