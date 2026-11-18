# T-Pot Honeypot Report - 2026-11-18T14:50:53Z

Source data: `20261118T144623Z` &nbsp;|&nbsp; Total events analyzed: **681685** &nbsp;|&nbsp; Unique attacker IPs: **5863**

Events by source: `honeypots`: 69224, `suricata`: 522294, `p0f`: 90167

_227204 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `78.107.31.154` | 40881 | Russia | Tula | OOO Gala-Centr MSK |
| `45.141.202.113` | 16854 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `80.91.71.147` | 2282 | Türkiye | Istanbul | Hostlayici Internet ve Bilisim Hizmetleri |
| `109.160.32.171` | 1474 | The Netherlands | Amsterdam | GBTCloud |
| `77.237.239.31` | 1375 | France | Lauterbourg | Contabo GmbH |
| `43.128.101.247` | 769 | Singapore | Singapore | Tencent Cloud Computing |
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

## Top Countries
| Country | Events |
|---|---:|
| Russia | 41024 |
| The Netherlands | 23907 |
| United States | 15140 |
| China | 3699 |
| Israel | 3583 |
| France | 2997 |
| Kazakhstan | 2943 |
| Germany | 2464 |
| Türkiye | 2359 |
| Singapore | 1412 |
| Hong Kong | 1184 |
| Poland | 1005 |
| United Kingdom | 774 |
| Japan | 529 |
| Hungary | 502 |
| Belgium | 500 |
| Brazil | 459 |
| Indonesia | 447 |
| India | 421 |
| Vietnam | 413 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 62680 |
| 443 | 23810 |
| 80 | 22814 |
| 64295 | 51 |
| 37208 | 7 |
| 60196 | 7 |
| 50136 | 3 |
| 43412 | 3 |
| 39950 | 2 |
| 38474 | 2 |
| 48596 | 2 |
| 46828 | 2 |
| 53280 | 2 |
| 57642 | 2 |
| 51254 | 2 |
| 56322 | 2 |
| 43596 | 2 |
| 36980 | 2 |
| 39992 | 2 |
| 58978 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `78.107.31.154` | 20093 |
| `109.160.32.171` | 679 |
| `43.128.101.247` | 381 |
| `83.168.110.67` | 301 |
| `47.113.193.48` | 266 |
| `125.39.11.27` | 159 |
| `47.251.165.65` | 151 |
| `180.76.228.8` | 134 |
| `210.195.210.116` | 105 |
| `109.160.32.123` | 64 |
| `118.70.239.231` | 62 |
| `103.72.57.129` | 45 |
| `8.217.68.84` | 32 |
| `4.4.66.84` | 31 |
| `223.243.179.70` | 31 |
| `50.114.172.201` | 31 |
| `94.204.5.49` | 31 |
| `49.12.249.111` | 31 |
| `213.215.209.101` | 31 |
| `60.165.119.59` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 12

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 61 |
| `140.248.150.49` | 59 |
| `146.75.30.49` | 27 |
| `67.202.15.124` | 9 |
| `185.125.188.59` | 9 |
| `185.125.188.54` | 9 |
| `185.125.188.57` | 9 |
| `185.125.188.55` | 9 |
| `185.125.188.60` | 8 |
| `185.125.188.58` | 8 |
| `54.224.99.219` | 5 |
| `54.234.187.186` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 28 |
| `root` | `admin` | 20 |
| `root` | `qwerty` | 18 |
| `root` | `root` | 18 |
| `root` | `ubuntu` | 17 |
| `root` | `passwd` | 17 |
| `root` | `guest` | 15 |
| `root` | `password` | 15 |
| `root` | `linux` | 14 |
| `root` | `apache` | 14 |
| `root` | `web` | 14 |
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
| 2026-10-20 | 880 |
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
| 2026-11-12 | 12077 |
| 2026-11-13 | 1521 |
| 2026-11-14 | 1481 |
| 2026-11-15 | 1376 |
| 2026-11-16 | 991 |
| 2026-11-17 | 1061 |
| 2026-11-18 | 513 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._