# T-Pot Honeypot Report - 2026-11-11T13:14:54Z

Source data: `20261111T131012Z` &nbsp;|&nbsp; Total events analyzed: **614249** &nbsp;|&nbsp; Unique attacker IPs: **6229**

Events by source: `honeypots`: 30339, `suricata`: 501103, `p0f`: 82807

_233379 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `45.141.202.113` | 16854 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `80.91.71.147` | 2282 | Türkiye | Istanbul | Hostlayici Internet ve Bilisim Hizmetleri |
| `109.160.32.171` | 1474 | The Netherlands | Amsterdam | GBTCloud |
| `77.237.239.31` | 1375 | France | Lauterbourg | Contabo GmbH |
| `77.91.71.90` | 908 | Israel | Tel Aviv | NEW |
| `135.148.217.213` | 771 | United States | New York | Cyera |
| `43.128.101.247` | 769 | Singapore | Singapore | Tencent Cloud Computing |
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
| The Netherlands | 24044 |
| United States | 15621 |
| Israel | 3886 |
| China | 3532 |
| France | 3133 |
| Kazakhstan | 2945 |
| Germany | 2654 |
| Türkiye | 2359 |
| Singapore | 1415 |
| Hong Kong | 1077 |
| United Kingdom | 952 |
| Poland | 905 |
| India | 732 |
| Belgium | 663 |
| Sweden | 610 |
| Thailand | 568 |
| Hungary | 557 |
| Japan | 524 |
| Brazil | 515 |
| Indonesia | 481 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 80 | 24435 |
| 443 | 23751 |
| 22 | 22877 |
| 64295 | 48 |
| 37208 | 7 |
| 33672 | 2 |
| 38630 | 2 |
| 48486 | 2 |
| 34048 | 2 |
| 37928 | 2 |
| 58618 | 2 |
| 42258 | 2 |
| 56322 | 2 |
| 57058 | 2 |
| 46828 | 2 |
| 57642 | 2 |
| 58978 | 2 |
| 40688 | 2 |
| 37174 | 2 |
| 36572 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `109.160.32.171` | 679 |
| `135.148.217.213` | 381 |
| `43.128.101.247` | 381 |
| `47.113.193.48` | 266 |
| `83.168.110.251` | 253 |
| `125.39.11.27` | 159 |
| `47.251.165.65` | 151 |
| `109.160.32.123` | 64 |
| `118.70.239.231` | 62 |
| `103.72.57.129` | 45 |
| `8.217.68.84` | 32 |
| `49.12.249.111` | 31 |
| `213.215.209.101` | 31 |
| `223.243.179.70` | 31 |
| `50.114.172.201` | 31 |
| `103.243.25.44` | 31 |
| `4.4.66.84` | 31 |
| `60.165.119.59` | 31 |
| `138.122.140.200` | 31 |
| `120.71.148.144` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 5

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 73 |
| `140.248.150.49` | 62 |
| `146.75.30.49` | 24 |
| `67.202.15.124` | 8 |
| `54.234.187.186` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 26 |
| `root` | `admin` | 21 |
| `root` | `ubuntu` | 19 |
| `root` | `password` | 19 |
| `root` | `passwd` | 19 |
| `root` | `root` | 19 |
| `root` | `qwerty` | 19 |
| `root` | `linux` | 18 |
| `root` | `apache` | 18 |
| `root` | `nginx` | 17 |
| `root` | `mysql` | 17 |
| `root` | `docker` | 17 |
| `root` | `vps` | 17 |
| `root` | `host` | 17 |
| `root` | `web` | 17 |
| `root` | `pass` | 17 |
| `root` | `guest` | 17 |
| `root` | `centos` | 16 |
| `root` | `www` | 16 |
| `root` | `default` | 16 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-12 | 2355 |
| 2026-10-13 | 1690 |
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
| 2026-11-11 | 461 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._