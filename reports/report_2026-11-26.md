# T-Pot Honeypot Report - 2026-11-26T16:03:28Z

Source data: `20261126T155911Z` &nbsp;|&nbsp; Total events analyzed: **662311** &nbsp;|&nbsp; Unique attacker IPs: **5847**

Events by source: `honeypots`: 68419, `suricata`: 513298, `p0f`: 80594

_226979 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `78.107.31.154` | 40881 | Russia | Tula | OOO Gala-Centr MSK |
| `45.141.202.113` | 16854 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `80.91.71.147` | 2282 | Türkiye | Istanbul | Hostlayici Internet ve Bilisim Hizmetleri |
| `164.68.122.8` | 2134 | France | Lauterbourg | Contabo GmbH |
| `109.160.32.171` | 1474 | The Netherlands | Amsterdam | GBTCloud |
| `77.237.239.31` | 622 | France | Lauterbourg | Contabo GmbH |
| `83.168.110.67` | 616 | Poland | Warsaw | SkillHost |
| `47.113.193.48` | 592 | China | Shenzhen | Aliyun Computing Co., LTD |
| `198.58.117.211` | 554 | United States | Richardson | Linode |
| `91.90.83.247` | 502 | United States | Seattle | UAB code200 |
| `43.226.39.177` | 430 | China | Haikuotiankong | Shenzhen APA Cloud Computing Co., Ltd |
| `47.111.170.178` | 409 | China | Hangzhou | Aliyun Computing Co., LTD |
| `77.91.71.24` | 367 | Israel | Tel Aviv | NEW |
| `162.0.232.217` | 365 | United States | Chicago | Namecheap, Inc. |
| `77.91.71.25` | 358 | Israel | Tel Aviv | NEW |
| `77.91.71.23` | 356 | Israel | Tel Aviv | NEW |
| `77.91.71.90` | 354 | Israel | Tel Aviv | NEW |
| `77.91.71.91` | 352 | Israel | Tel Aviv | NEW |
| `185.136.15.111` | 351 | Kazakhstan | Almaty | Vlad Cojuhari |
| `185.136.15.82` | 350 | Kazakhstan | Almaty | Vlad Cojuhari |

## Top Countries
| Country | Events |
|---|---:|
| Russia | 41015 |
| The Netherlands | 23028 |
| United States | 14859 |
| France | 4215 |
| China | 3524 |
| Germany | 2518 |
| Türkiye | 2375 |
| Israel | 2160 |
| Kazakhstan | 1826 |
| Hong Kong | 1220 |
| Poland | 999 |
| United Kingdom | 737 |
| Belgium | 510 |
| Brazil | 505 |
| Singapore | 502 |
| Hungary | 477 |
| Japan | 457 |
| Vietnam | 405 |
| Canada | 367 |
| Andorra | 360 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 58651 |
| 443 | 23432 |
| 80 | 23236 |
| 64295 | 42 |
| 37208 | 7 |
| 60196 | 7 |
| 48166 | 6 |
| 43412 | 3 |
| 41840 | 2 |
| 35342 | 2 |
| 38474 | 2 |
| 48486 | 2 |
| 57642 | 2 |
| 39950 | 2 |
| 45554 | 2 |
| 42156 | 2 |
| 58978 | 2 |
| 36572 | 2 |
| 33868 | 2 |
| 47956 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `78.107.31.154` | 20093 |
| `109.160.32.171` | 679 |
| `83.168.110.67` | 301 |
| `47.113.193.48` | 266 |
| `43.226.39.177` | 169 |
| `125.39.11.27` | 159 |
| `47.251.165.65` | 151 |
| `180.76.228.8` | 134 |
| `210.195.210.116` | 105 |
| `109.160.32.176` | 83 |
| `118.70.239.231` | 62 |
| `103.72.57.129` | 45 |
| `8.217.68.84` | 32 |
| `42.236.73.142` | 31 |
| `4.4.66.84` | 31 |
| `50.114.172.201` | 31 |
| `49.12.249.111` | 31 |
| `213.215.209.101` | 31 |
| `138.122.140.200` | 31 |
| `94.204.5.49` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 11

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 37 |
| `140.248.150.49` | 26 |
| `146.75.30.49` | 24 |
| `185.125.188.54` | 9 |
| `185.125.188.59` | 9 |
| `185.125.188.57` | 9 |
| `185.125.188.55` | 9 |
| `185.125.188.60` | 8 |
| `185.125.188.58` | 8 |
| `67.202.15.124` | 6 |
| `54.234.187.186` | 6 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 25 |
| `root` | `admin` | 18 |
| `root` | `root` | 16 |
| `root` | `ubuntu` | 15 |
| `root` | `qwerty` | 15 |
| `root` | `passwd` | 14 |
| `root` | `linux` | 13 |
| `root` | `guest` | 12 |
| `root` | `web` | 12 |
| `root` | `debian` | 12 |
| `root` | `` | 11 |
| `root` | `password` | 11 |
| `root` | `apache` | 11 |
| `root` | `centos` | 11 |
| `root` | `pass` | 11 |
| `root` | `temp` | 11 |
| `root` | `test` | 11 |
| `root` | `nginx` | 10 |
| `root` | `mysql` | 10 |
| `root` | `docker` | 10 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-28 | 6602 |
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
| 2026-11-23 | 922 |
| 2026-11-24 | 1095 |
| 2026-11-25 | 3376 |
| 2026-11-26 | 501 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._