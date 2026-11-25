# T-Pot Honeypot Report - 2026-11-25T16:29:48Z

Source data: `20261125T162526Z` &nbsp;|&nbsp; Total events analyzed: **669394** &nbsp;|&nbsp; Unique attacker IPs: **5848**

Events by source: `honeypots`: 68698, `suricata`: 515392, `p0f`: 85304

_227536 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

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
| `77.91.71.24` | 413 | Israel | Tel Aviv | NEW |
| `47.111.170.178` | 409 | China | Hangzhou | Aliyun Computing Co., LTD |
| `77.91.71.25` | 404 | Israel | Tel Aviv | NEW |
| `77.91.71.90` | 402 | Israel | Tel Aviv | NEW |
| `77.91.71.23` | 400 | Israel | Tel Aviv | NEW |
| `185.136.15.82` | 396 | Kazakhstan | Almaty | Vlad Cojuhari |
| `77.91.71.91` | 396 | Israel | Tel Aviv | NEW |
| `185.136.15.111` | 395 | Kazakhstan | Almaty | Vlad Cojuhari |
| `185.136.15.81` | 394 | Kazakhstan | Almaty | Vlad Cojuhari |

## Top Countries
| Country | Events |
|---|---:|
| Russia | 41008 |
| The Netherlands | 23161 |
| United States | 14552 |
| France | 4199 |
| China | 3580 |
| Germany | 2539 |
| Israel | 2430 |
| Türkiye | 2375 |
| Kazakhstan | 2055 |
| Hong Kong | 1223 |
| Poland | 1010 |
| United Kingdom | 730 |
| Unknown | 589 |
| Singapore | 492 |
| Belgium | 492 |
| Brazil | 484 |
| Hungary | 477 |
| Japan | 460 |
| Vietnam | 407 |
| Andorra | 365 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 59386 |
| 443 | 23442 |
| 80 | 23356 |
| 64295 | 43 |
| 60196 | 7 |
| 37208 | 7 |
| 48166 | 6 |
| 43412 | 3 |
| 42156 | 2 |
| 38750 | 2 |
| 39950 | 2 |
| 45554 | 2 |
| 33672 | 2 |
| 56522 | 2 |
| 53062 | 2 |
| 50136 | 2 |
| 53492 | 2 |
| 46624 | 2 |
| 39462 | 2 |
| 45524 | 2 |

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
| `50.114.172.201` | 31 |
| `120.71.148.144` | 31 |
| `42.236.73.142` | 31 |
| `60.165.119.59` | 31 |
| `49.12.249.111` | 31 |
| `213.215.209.101` | 31 |
| `4.4.66.84` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 11

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 35 |
| `140.248.150.49` | 28 |
| `146.75.30.49` | 24 |
| `185.125.188.59` | 9 |
| `185.125.188.55` | 9 |
| `185.125.188.57` | 9 |
| `185.125.188.54` | 9 |
| `185.125.188.58` | 8 |
| `185.125.188.60` | 8 |
| `67.202.15.124` | 7 |
| `54.234.187.186` | 6 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 26 |
| `root` | `admin` | 19 |
| `root` | `root` | 17 |
| `root` | `qwerty` | 16 |
| `root` | `ubuntu` | 16 |
| `root` | `passwd` | 15 |
| `root` | `linux` | 14 |
| `root` | `debian` | 13 |
| `root` | `web` | 13 |
| `root` | `guest` | 13 |
| `root` | `centos` | 12 |
| `root` | `apache` | 12 |
| `root` | `password` | 12 |
| `root` | `pass` | 12 |
| `root` | `temp` | 12 |
| `root` | `test` | 12 |
| `root` | `nginx` | 11 |
| `root` | `mysql` | 11 |
| `root` | `docker` | 11 |
| `root` | `vps` | 11 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-27 | 1361 |
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
| 2026-11-23 | 922 |
| 2026-11-24 | 1095 |
| 2026-11-25 | 3146 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._