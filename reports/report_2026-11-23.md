# T-Pot Honeypot Report - 2026-11-23T16:52:34Z

Source data: `20261123T164806Z` &nbsp;|&nbsp; Total events analyzed: **668456** &nbsp;|&nbsp; Unique attacker IPs: **5862**

Events by source: `honeypots`: 68231, `suricata`: 514620, `p0f`: 85605

_226653 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `78.107.31.154` | 40881 | Russia | Tula | OOO Gala-Centr MSK |
| `45.141.202.113` | 16854 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `80.91.71.147` | 2282 | Türkiye | Istanbul | Hostlayici Internet ve Bilisim Hizmetleri |
| `109.160.32.171` | 1474 | The Netherlands | Amsterdam | GBTCloud |
| `77.237.239.31` | 1375 | France | Lauterbourg | Contabo GmbH |
| `83.168.110.67` | 616 | Poland | Warsaw | SkillHost |
| `47.113.193.48` | 592 | China | Shenzhen | Aliyun Computing Co., LTD |
| `198.58.117.211` | 554 | United States | Richardson | Linode |
| `77.91.71.24` | 503 | Israel | Tel Aviv | NEW |
| `91.90.83.247` | 502 | United States | Seattle | UAB code200 |
| `77.91.71.90` | 498 | Israel | Tel Aviv | NEW |
| `77.91.71.91` | 494 | Israel | Tel Aviv | NEW |
| `185.136.15.111` | 493 | Kazakhstan | Almaty | Vlad Cojuhari |
| `77.91.71.25` | 492 | Israel | Tel Aviv | NEW |
| `77.91.71.23` | 490 | Israel | Tel Aviv | NEW |
| `185.136.15.110` | 490 | Kazakhstan | Almaty | Vlad Cojuhari |
| `185.136.15.80` | 488 | Kazakhstan | Almaty | Vlad Cojuhari |
| `185.136.15.82` | 486 | Kazakhstan | Almaty | Vlad Cojuhari |
| `185.136.15.81` | 482 | Kazakhstan | Almaty | Vlad Cojuhari |
| `138.226.239.91` | 470 | The Netherlands | Amsterdam | Vlad Cojuhari |

## Top Countries
| Country | Events |
|---|---:|
| Russia | 41006 |
| The Netherlands | 23194 |
| United States | 15302 |
| China | 3873 |
| Israel | 2993 |
| France | 2869 |
| Kazakhstan | 2526 |
| Germany | 2501 |
| Türkiye | 2361 |
| Hong Kong | 1220 |
| Poland | 1007 |
| United Kingdom | 713 |
| Belgium | 518 |
| Hungary | 489 |
| Singapore | 480 |
| Brazil | 469 |
| Japan | 469 |
| Indonesia | 457 |
| Vietnam | 405 |
| Andorra | 360 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 60124 |
| 443 | 23564 |
| 80 | 23003 |
| 64295 | 49 |
| 60196 | 7 |
| 37208 | 7 |
| 43412 | 3 |
| 54932 | 2 |
| 42024 | 2 |
| 54810 | 2 |
| 36572 | 2 |
| 57642 | 2 |
| 34048 | 2 |
| 53280 | 2 |
| 53284 | 2 |
| 35298 | 2 |
| 35130 | 2 |
| 46828 | 2 |
| 36980 | 2 |
| 35342 | 2 |

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
| `50.114.172.201` | 31 |
| `49.12.249.111` | 31 |
| `213.215.209.101` | 31 |
| `138.122.140.200` | 31 |
| `94.204.5.49` | 31 |
| `42.236.73.142` | 31 |
| `101.47.28.226` | 31 |
| `60.165.119.59` | 31 |
| `4.4.66.84` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 12

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 42 |
| `140.248.150.49` | 42 |
| `146.75.30.49` | 27 |
| `185.125.188.54` | 9 |
| `185.125.188.59` | 9 |
| `185.125.188.55` | 9 |
| `185.125.188.57` | 9 |
| `185.125.188.58` | 8 |
| `185.125.188.60` | 8 |
| `67.202.15.124` | 7 |
| `54.234.187.186` | 6 |
| `54.224.99.219` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 26 |
| `root` | `admin` | 20 |
| `root` | `root` | 18 |
| `root` | `ubuntu` | 17 |
| `root` | `qwerty` | 16 |
| `root` | `passwd` | 15 |
| `root` | `debian` | 14 |
| `root` | `linux` | 14 |
| `root` | `web` | 14 |
| `root` | `guest` | 14 |
| `root` | `centos` | 13 |
| `root` | `apache` | 13 |
| `root` | `password` | 13 |
| `root` | `pass` | 13 |
| `root` | `temp` | 13 |
| `root` | `test` | 13 |
| `root` | `nginx` | 12 |
| `root` | `mysql` | 12 |
| `root` | `docker` | 12 |
| `root` | `vps` | 12 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-25 | 1877 |
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
| 2026-11-20 | 1286 |
| 2026-11-21 | 815 |
| 2026-11-22 | 1463 |
| 2026-11-23 | 699 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._