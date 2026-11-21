# T-Pot Honeypot Report - 2026-11-21T13:57:02Z

Source data: `20261121T135240Z` &nbsp;|&nbsp; Total events analyzed: **673849** &nbsp;|&nbsp; Unique attacker IPs: **5829**

Events by source: `honeypots`: 68339, `suricata`: 517890, `p0f`: 87620

_226247 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `78.107.31.154` | 40881 | Russia | Tula | OOO Gala-Centr MSK |
| `45.141.202.113` | 16854 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `80.91.71.147` | 2282 | Türkiye | Istanbul | Hostlayici Internet ve Bilisim Hizmetleri |
| `109.160.32.171` | 1474 | The Netherlands | Amsterdam | GBTCloud |
| `77.237.239.31` | 1375 | France | Lauterbourg | Contabo GmbH |
| `83.168.110.67` | 616 | Poland | Warsaw | SkillHost |
| `77.91.71.90` | 592 | Israel | Tel Aviv | NEW |
| `47.113.193.48` | 592 | China | Shenzhen | Aliyun Computing Co., LTD |
| `77.91.71.91` | 588 | Israel | Tel Aviv | NEW |
| `138.226.239.91` | 578 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `77.91.71.24` | 575 | Israel | Tel Aviv | NEW |
| `185.136.15.111` | 563 | Kazakhstan | Almaty | Vlad Cojuhari |
| `77.91.71.25` | 561 | Israel | Tel Aviv | NEW |
| `185.136.15.82` | 559 | Kazakhstan | Almaty | Vlad Cojuhari |
| `185.136.15.110` | 558 | Kazakhstan | Almaty | Vlad Cojuhari |
| `77.91.71.92` | 557 | Israel | Tel Aviv | NEW |
| `77.91.71.23` | 557 | Israel | Tel Aviv | NEW |
| `185.136.15.81` | 554 | Kazakhstan | Almaty | Vlad Cojuhari |
| `185.136.15.80` | 554 | Kazakhstan | Almaty | Vlad Cojuhari |
| `198.58.117.211` | 554 | United States | Richardson | Linode |

## Top Countries
| Country | Events |
|---|---:|
| Russia | 40993 |
| The Netherlands | 23702 |
| United States | 15161 |
| China | 3617 |
| Israel | 3481 |
| France | 2893 |
| Kazakhstan | 2877 |
| Germany | 2486 |
| Türkiye | 2356 |
| Hong Kong | 1212 |
| Poland | 1003 |
| United Kingdom | 738 |
| Hungary | 624 |
| Singapore | 545 |
| Belgium | 483 |
| Japan | 460 |
| Brazil | 457 |
| Indonesia | 448 |
| India | 433 |
| Unknown | 432 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 61585 |
| 443 | 23686 |
| 80 | 22990 |
| 64295 | 50 |
| 60196 | 7 |
| 37208 | 7 |
| 43412 | 3 |
| 59346 | 2 |
| 36572 | 2 |
| 39992 | 2 |
| 53280 | 2 |
| 53284 | 2 |
| 46828 | 2 |
| 33672 | 2 |
| 56522 | 2 |
| 53062 | 2 |
| 50136 | 2 |
| 53492 | 2 |
| 46624 | 2 |
| 39462 | 2 |

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
| `94.204.5.49` | 31 |
| `120.71.148.144` | 31 |
| `223.243.179.70` | 31 |
| `49.12.249.111` | 31 |
| `213.215.209.101` | 31 |
| `50.114.172.201` | 31 |
| `4.4.66.84` | 31 |
| `138.122.140.200` | 31 |
| `42.236.73.142` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 12

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 55 |
| `140.248.150.49` | 55 |
| `146.75.30.49` | 29 |
| `185.125.188.59` | 9 |
| `185.125.188.55` | 9 |
| `185.125.188.57` | 9 |
| `185.125.188.54` | 9 |
| `67.202.15.124` | 8 |
| `185.125.188.58` | 8 |
| `185.125.188.60` | 8 |
| `54.234.187.186` | 6 |
| `54.224.99.219` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 25 |
| `root` | `admin` | 18 |
| `root` | `root` | 16 |
| `root` | `qwerty` | 16 |
| `root` | `ubuntu` | 15 |
| `root` | `passwd` | 15 |
| `root` | `guest` | 14 |
| `root` | `apache` | 13 |
| `root` | `web` | 13 |
| `root` | `linux` | 13 |
| `root` | `pass` | 13 |
| `root` | `temp` | 13 |
| `root` | `test` | 13 |
| `root` | `password` | 13 |
| `root` | `debian` | 12 |
| `root` | `centos` | 12 |
| `root` | `nginx` | 12 |
| `root` | `mysql` | 12 |
| `root` | `docker` | 12 |
| `root` | `vps` | 12 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-23 | 1993 |
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
| 2026-11-20 | 1286 |
| 2026-11-21 | 458 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._