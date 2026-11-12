# T-Pot Honeypot Report - 2026-11-12T14:17:44Z

Source data: `20261112T141306Z` &nbsp;|&nbsp; Total events analyzed: **709792** &nbsp;|&nbsp; Unique attacker IPs: **6174**

Events by source: `honeypots`: 69874, `suricata`: 540115, `p0f`: 99803

_233676 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `78.107.31.154` | 40881 | Russia | Tula | OOO Gala-Centr MSK |
| `45.141.202.113` | 16854 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `80.91.71.147` | 2282 | Türkiye | Istanbul | Hostlayici Internet ve Bilisim Hizmetleri |
| `109.160.32.171` | 1474 | The Netherlands | Amsterdam | GBTCloud |
| `77.237.239.31` | 1375 | France | Lauterbourg | Contabo GmbH |
| `43.128.101.247` | 769 | Singapore | Singapore | Tencent Cloud Computing |
| `77.91.71.90` | 740 | Israel | Tel Aviv | NEW |
| `83.168.110.67` | 616 | Poland | Warsaw | SkillHost |
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

## Top Countries
| Country | Events |
|---|---:|
| Russia | 41035 |
| The Netherlands | 24064 |
| United States | 14683 |
| Israel | 3709 |
| China | 3531 |
| France | 3118 |
| Kazakhstan | 2946 |
| Germany | 2682 |
| Türkiye | 2361 |
| Poland | 1517 |
| Singapore | 1486 |
| Hong Kong | 1041 |
| United Kingdom | 999 |
| India | 730 |
| Hungary | 601 |
| Sweden | 569 |
| Belgium | 561 |
| Japan | 527 |
| Brazil | 513 |
| Indonesia | 480 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 63493 |
| 80 | 23870 |
| 443 | 23821 |
| 64295 | 49 |
| 37208 | 7 |
| 60196 | 7 |
| 50136 | 3 |
| 43412 | 3 |
| 33868 | 2 |
| 47956 | 2 |
| 58424 | 2 |
| 42024 | 2 |
| 54810 | 2 |
| 36572 | 2 |
| 38630 | 2 |
| 40688 | 2 |
| 37174 | 2 |
| 42258 | 2 |
| 37928 | 2 |
| 43596 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `78.107.31.154` | 20093 |
| `109.160.32.171` | 679 |
| `43.128.101.247` | 381 |
| `83.168.110.67` | 301 |
| `47.113.193.48` | 266 |
| `83.168.110.251` | 253 |
| `125.39.11.27` | 159 |
| `47.251.165.65` | 151 |
| `109.160.32.123` | 64 |
| `118.70.239.231` | 62 |
| `103.72.57.129` | 45 |
| `8.217.68.84` | 32 |
| `60.165.119.59` | 31 |
| `154.211.13.102` | 31 |
| `42.101.60.58` | 31 |
| `223.243.179.70` | 31 |
| `138.122.140.200` | 31 |
| `101.47.28.226` | 31 |
| `49.12.249.111` | 31 |
| `213.215.209.101` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 12

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 70 |
| `140.248.150.49` | 62 |
| `146.75.30.49` | 25 |
| `185.125.188.59` | 9 |
| `185.125.188.54` | 9 |
| `67.202.15.124` | 8 |
| `185.125.188.55` | 8 |
| `185.125.188.57` | 8 |
| `185.125.188.58` | 8 |
| `185.125.188.60` | 7 |
| `54.234.187.186` | 6 |
| `44.200.226.78` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 25 |
| `root` | `admin` | 20 |
| `root` | `ubuntu` | 19 |
| `root` | `passwd` | 19 |
| `root` | `linux` | 18 |
| `root` | `apache` | 18 |
| `root` | `password` | 18 |
| `root` | `root` | 18 |
| `root` | `qwerty` | 18 |
| `root` | `nginx` | 17 |
| `root` | `mysql` | 17 |
| `root` | `docker` | 17 |
| `root` | `vps` | 17 |
| `root` | `host` | 17 |
| `root` | `web` | 17 |
| `root` | `default` | 17 |
| `root` | `pass` | 17 |
| `root` | `temp` | 17 |
| `root` | `guest` | 17 |
| `root` | `centos` | 16 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-13 | 1403 |
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
| 2026-11-12 | 11528 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._