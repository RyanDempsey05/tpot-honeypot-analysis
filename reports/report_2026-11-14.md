# T-Pot Honeypot Report - 2026-11-14T12:45:51Z

Source data: `20261114T124124Z` &nbsp;|&nbsp; Total events analyzed: **688529** &nbsp;|&nbsp; Unique attacker IPs: **5985**

Events by source: `honeypots`: 69016, `suricata`: 527100, `p0f`: 92413

_226212 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

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
| `77.91.71.91` | 609 | Israel | Tel Aviv | NEW |
| `77.91.71.90` | 608 | Israel | Tel Aviv | NEW |
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
| Russia | 41027 |
| The Netherlands | 23895 |
| United States | 14322 |
| China | 3851 |
| Israel | 3581 |
| France | 2967 |
| Kazakhstan | 2949 |
| Germany | 2418 |
| Türkiye | 2361 |
| Poland | 1524 |
| Singapore | 1459 |
| Hong Kong | 1061 |
| United Kingdom | 920 |
| Hungary | 603 |
| Japan | 523 |
| Belgium | 515 |
| Brazil | 487 |
| Indonesia | 452 |
| Sweden | 435 |
| India | 416 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 63511 |
| 443 | 23341 |
| 80 | 22661 |
| 64295 | 50 |
| 37208 | 7 |
| 60196 | 7 |
| 50136 | 3 |
| 43412 | 3 |
| 39992 | 2 |
| 34048 | 2 |
| 35342 | 2 |
| 38474 | 2 |
| 36366 | 2 |
| 57058 | 2 |
| 55764 | 2 |
| 56322 | 2 |
| 33672 | 2 |
| 56522 | 2 |
| 53062 | 2 |
| 53492 | 2 |

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
| `180.76.228.8` | 134 |
| `210.195.210.116` | 105 |
| `109.160.32.123` | 64 |
| `118.70.239.231` | 62 |
| `103.72.57.129` | 45 |
| `8.217.68.84` | 32 |
| `4.4.66.84` | 31 |
| `60.165.119.59` | 31 |
| `121.227.31.82` | 31 |
| `49.12.249.111` | 31 |
| `213.215.209.101` | 31 |
| `113.98.254.50` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 13

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 72 |
| `140.248.150.49` | 58 |
| `146.75.30.49` | 25 |
| `185.125.188.54` | 9 |
| `185.125.188.59` | 9 |
| `185.125.188.55` | 9 |
| `185.125.188.57` | 9 |
| `67.202.15.124` | 8 |
| `185.125.188.58` | 8 |
| `185.125.188.60` | 8 |
| `54.234.187.186` | 6 |
| `44.200.226.78` | 5 |
| `54.224.99.219` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 27 |
| `root` | `admin` | 21 |
| `root` | `ubuntu` | 19 |
| `root` | `passwd` | 19 |
| `root` | `qwerty` | 19 |
| `root` | `password` | 18 |
| `root` | `root` | 18 |
| `root` | `linux` | 17 |
| `root` | `apache` | 17 |
| `root` | `guest` | 17 |
| `root` | `nginx` | 16 |
| `root` | `mysql` | 16 |
| `root` | `docker` | 16 |
| `root` | `vps` | 16 |
| `root` | `host` | 16 |
| `root` | `web` | 16 |
| `root` | `default` | 16 |
| `root` | `pass` | 16 |
| `root` | `temp` | 16 |
| `root` | `debian` | 15 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-16 | 987 |
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
| 2026-11-12 | 12077 |
| 2026-11-13 | 1521 |
| 2026-11-14 | 439 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._