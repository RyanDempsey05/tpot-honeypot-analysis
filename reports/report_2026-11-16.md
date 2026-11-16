# T-Pot Honeypot Report - 2026-11-16T14:19:49Z

Source data: `20261116T141522Z` &nbsp;|&nbsp; Total events analyzed: **685861** &nbsp;|&nbsp; Unique attacker IPs: **5933**

Events by source: `honeypots`: 69225, `suricata`: 525532, `p0f`: 91104

_227221 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

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
| Russia | 41031 |
| The Netherlands | 23913 |
| United States | 15192 |
| China | 3789 |
| Israel | 3581 |
| Kazakhstan | 2944 |
| France | 2910 |
| Germany | 2464 |
| Türkiye | 2359 |
| Singapore | 1408 |
| Hong Kong | 1103 |
| Poland | 1001 |
| United Kingdom | 829 |
| Japan | 530 |
| Hungary | 506 |
| Brazil | 494 |
| Belgium | 461 |
| Indonesia | 443 |
| India | 418 |
| Vietnam | 412 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 62785 |
| 443 | 23844 |
| 80 | 22882 |
| 64295 | 50 |
| 60196 | 7 |
| 37208 | 7 |
| 50136 | 3 |
| 43412 | 3 |
| 55136 | 2 |
| 33672 | 2 |
| 56522 | 2 |
| 53062 | 2 |
| 53492 | 2 |
| 46624 | 2 |
| 39462 | 2 |
| 45524 | 2 |
| 56556 | 2 |
| 35438 | 2 |
| 46608 | 2 |
| 59114 | 2 |

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
| `138.122.140.200` | 31 |
| `113.98.254.50` | 31 |
| `50.114.172.201` | 31 |
| `94.204.5.49` | 31 |
| `101.47.28.226` | 31 |
| `121.227.31.82` | 31 |
| `120.71.148.144` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 13

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 79 |
| `140.248.150.49` | 64 |
| `146.75.30.49` | 27 |
| `67.202.15.124` | 9 |
| `185.125.188.59` | 9 |
| `185.125.188.55` | 9 |
| `185.125.188.57` | 9 |
| `185.125.188.54` | 9 |
| `185.125.188.58` | 8 |
| `185.125.188.60` | 8 |
| `44.200.226.78` | 5 |
| `54.234.187.186` | 5 |
| `54.224.99.219` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 29 |
| `root` | `admin` | 21 |
| `root` | `qwerty` | 20 |
| `root` | `root` | 19 |
| `root` | `ubuntu` | 19 |
| `root` | `passwd` | 19 |
| `root` | `password` | 17 |
| `root` | `guest` | 17 |
| `root` | `apache` | 16 |
| `root` | `web` | 16 |
| `root` | `linux` | 16 |
| `root` | `pass` | 16 |
| `root` | `temp` | 16 |
| `root` | `test` | 16 |
| `root` | `debian` | 15 |
| `root` | `centos` | 15 |
| `root` | `nginx` | 15 |
| `root` | `mysql` | 15 |
| `root` | `docker` | 15 |
| `root` | `vps` | 15 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-18 | 838 |
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
| 2026-11-14 | 1481 |
| 2026-11-15 | 1376 |
| 2026-11-16 | 627 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._