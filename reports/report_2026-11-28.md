# T-Pot Honeypot Report - 2026-11-28T14:47:53Z

Source data: `20261128T144329Z` &nbsp;|&nbsp; Total events analyzed: **631127** &nbsp;|&nbsp; Unique attacker IPs: **5847**

Events by source: `honeypots`: 65155, `suricata`: 493208, `p0f`: 72764

_223513 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `78.107.31.154` | 40881 | Russia | Tula | OOO Gala-Centr MSK |
| `45.141.202.113` | 12528 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `80.91.71.147` | 2282 | Türkiye | Istanbul | Hostlayici Internet ve Bilisim Hizmetleri |
| `164.68.122.8` | 2134 | France | Lauterbourg | Contabo GmbH |
| `109.160.32.171` | 1474 | The Netherlands | Amsterdam | GBTCloud |
| `93.152.209.6` | 661 | China | Haidian | Dedik Services Limited |
| `83.168.110.67` | 616 | Poland | Warsaw | SkillHost |
| `47.113.193.48` | 592 | China | Shenzhen | Aliyun Computing Co., LTD |
| `198.58.117.211` | 554 | United States | Richardson | Linode |
| `91.90.83.247` | 502 | United States | Seattle | UAB code200 |
| `43.226.39.177` | 426 | China | Haikuotiankong | Shenzhen APA Cloud Computing Co., Ltd |
| `47.111.170.178` | 409 | China | Hangzhou | Aliyun Computing Co., LTD |
| `162.0.232.217` | 365 | United States | Chicago | Namecheap, Inc. |
| `125.39.11.27` | 350 | China | Tianjin |  |
| `180.76.228.8` | 344 | China | Beijing | Beijing Baidu Netcom Science and Technology Co., Ltd. |
| `5.253.235.91` | 340 | United States | Washington | Packethub S.A |
| `47.251.165.65` | 333 | United States | Minkler | Alibaba Cloud - US |
| `8.217.99.120` | 315 | Hong Kong | Hong Kong | Alibaba.com Singapore E-Commerce Private Limited |
| `138.226.239.233` | 308 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `138.226.239.234` | 282 | The Netherlands | Amsterdam | Vlad Cojuhari |

## Top Countries
| Country | Events |
|---|---:|
| Russia | 41013 |
| The Netherlands | 18435 |
| United States | 14606 |
| China | 3851 |
| France | 3530 |
| Germany | 2463 |
| Türkiye | 2378 |
| Israel | 1619 |
| Kazakhstan | 1369 |
| Hong Kong | 1215 |
| Poland | 984 |
| United Kingdom | 759 |
| Brazil | 539 |
| Singapore | 490 |
| Belgium | 483 |
| Hungary | 472 |
| Japan | 450 |
| Canada | 405 |
| Andorra | 371 |
| Vietnam | 307 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 57152 |
| 443 | 23341 |
| 80 | 18411 |
| 64295 | 41 |
| 60196 | 7 |
| 37208 | 7 |
| 48166 | 6 |
| 55958 | 2 |
| 33672 | 2 |
| 56522 | 2 |
| 53062 | 2 |
| 50136 | 2 |
| 53492 | 2 |
| 46624 | 2 |
| 39462 | 2 |
| 45524 | 2 |
| 56556 | 2 |
| 35438 | 2 |
| 43412 | 2 |
| 46608 | 2 |

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
| `8.217.68.84` | 32 |
| `50.114.172.201` | 31 |
| `138.122.140.200` | 31 |
| `94.204.5.49` | 31 |
| `101.47.28.226` | 31 |
| `42.236.73.142` | 31 |
| `4.4.66.84` | 31 |
| `49.72.111.25` | 30 |
| `47.111.170.178` | 29 |

**Likely port-scan sources** (>= 5 distinct ports touched): 12

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 39 |
| `140.248.150.49` | 26 |
| `146.75.30.49` | 22 |
| `185.125.188.59` | 9 |
| `185.125.188.55` | 9 |
| `185.125.188.57` | 9 |
| `185.125.188.54` | 9 |
| `185.125.188.58` | 8 |
| `185.125.188.60` | 8 |
| `67.202.15.124` | 6 |
| `54.234.187.186` | 5 |
| `100.48.216.11` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 22 |
| `root` | `admin` | 16 |
| `root` | `root` | 14 |
| `root` | `ubuntu` | 13 |
| `root` | `qwerty` | 13 |
| `root` | `passwd` | 12 |
| `root` | `linux` | 11 |
| `root` | `` | 11 |
| `root` | `debian` | 10 |
| `root` | `web` | 10 |
| `root` | `guest` | 10 |
| `root` | `centos` | 9 |
| `root` | `apache` | 9 |
| `root` | `password` | 9 |
| `root` | `pass` | 9 |
| `root` | `temp` | 9 |
| `root` | `test` | 9 |
| `root` | `nginx` | 8 |
| `root` | `mysql` | 8 |
| `root` | `docker` | 8 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-30 | 1374 |
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
| 2026-11-26 | 774 |
| 2026-11-27 | 880 |
| 2026-11-28 | 903 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._