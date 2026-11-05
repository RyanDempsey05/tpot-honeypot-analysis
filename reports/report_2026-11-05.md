# T-Pot Honeypot Report - 2026-11-05T13:46:09Z

Source data: `20261105T134127Z` &nbsp;|&nbsp; Total events analyzed: **673245** &nbsp;|&nbsp; Unique attacker IPs: **6372**

Events by source: `honeypots`: 51353, `suricata`: 529873, `p0f`: 92019

_240786 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `45.141.202.113` | 16854 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `80.91.71.147` | 2282 | Türkiye | Istanbul | Hostlayici Internet ve Bilisim Hizmetleri |
| `77.91.71.90` | 1902 | Israel | Tel Aviv | NEW |
| `77.237.239.31` | 1375 | France | Lauterbourg | Contabo GmbH |
| `77.239.124.36` | 1146 | France | Paris | RocketCloud |
| `135.148.217.213` | 771 | United States | New York | Cyera |
| `43.128.101.247` | 769 | Singapore | Singapore | Tencent Cloud Computing |
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
| `77.91.71.91` | 609 | Israel | Tel Aviv | NEW |
| `138.226.239.91` | 599 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `47.113.193.48` | 591 | China | Shenzhen | Aliyun Computing Co., LTD |
| `77.91.71.24` | 583 | Israel | Tel Aviv | NEW |
| `185.136.15.111` | 575 | Kazakhstan | Almaty | Vlad Cojuhari |
| `77.91.71.92` | 574 | Israel | Tel Aviv | NEW |
| `77.91.71.25` | 572 | Israel | Tel Aviv | NEW |
| `77.91.71.23` | 571 | Israel | Tel Aviv | NEW |
| `185.136.15.82` | 570 | Kazakhstan | Almaty | Vlad Cojuhari |

## Top Countries
| Country | Events |
|---|---:|
| The Netherlands | 22526 |
| United States | 16788 |
| Mauritius | 12732 |
| France | 7054 |
| China | 5950 |
| Israel | 4874 |
| Kazakhstan | 2941 |
| Germany | 2613 |
| Türkiye | 2325 |
| Singapore | 1577 |
| Hong Kong | 1095 |
| United Kingdom | 999 |
| Poland | 889 |
| Sweden | 847 |
| India | 754 |
| Belgium | 735 |
| Japan | 602 |
| Hungary | 560 |
| Thailand | 552 |
| Canada | 513 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 38870 |
| 80 | 28701 |
| 443 | 24142 |
| 64295 | 48 |
| 40692 | 7 |
| 37208 | 7 |
| 48486 | 2 |
| 33382 | 2 |
| 56322 | 2 |
| 36572 | 2 |
| 36980 | 2 |
| 37928 | 2 |
| 51254 | 2 |
| 38630 | 2 |
| 39950 | 2 |
| 36366 | 2 |
| 38474 | 2 |
| 58424 | 2 |
| 40688 | 2 |
| 37174 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `196.20.216.206` | 5778 |
| `106.38.51.68` | 1286 |
| `77.239.124.36` | 513 |
| `43.128.101.247` | 381 |
| `135.148.217.213` | 381 |
| `47.113.193.48` | 266 |
| `83.168.110.251` | 253 |
| `47.251.165.65` | 151 |
| `91.218.108.6` | 104 |
| `109.160.32.123` | 64 |
| `77.91.71.90` | 53 |
| `103.72.57.129` | 45 |
| `8.217.68.84` | 32 |
| `50.114.172.201` | 31 |
| `60.165.119.59` | 31 |
| `113.98.254.50` | 31 |
| `154.211.13.102` | 31 |
| `42.101.60.58` | 31 |
| `121.227.31.82` | 31 |
| `223.243.179.70` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 5

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 76 |
| `140.248.150.49` | 64 |
| `146.75.30.49` | 24 |
| `67.202.15.124` | 8 |
| `54.224.99.219` | 7 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 24 |
| `root` | `ubuntu` | 21 |
| `root` | `admin` | 20 |
| `root` | `root` | 20 |
| `root` | `password` | 20 |
| `root` | `linux` | 19 |
| `root` | `passwd` | 19 |
| `root` | `apache` | 18 |
| `root` | `guest` | 18 |
| `root` | `qwerty` | 18 |
| `root` | `centos` | 17 |
| `root` | `nginx` | 17 |
| `root` | `mysql` | 17 |
| `root` | `docker` | 17 |
| `root` | `vps` | 17 |
| `root` | `host` | 17 |
| `root` | `www` | 17 |
| `root` | `web` | 17 |
| `root` | `default` | 17 |
| `root` | `administrator` | 17 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-06 | 1004 |
| 2026-10-07 | 6194 |
| 2026-10-08 | 1248 |
| 2026-10-09 | 4361 |
| 2026-10-10 | 14015 |
| 2026-10-11 | 1189 |
| 2026-10-12 | 2661 |
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
| 2026-11-05 | 697 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._