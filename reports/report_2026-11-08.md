# T-Pot Honeypot Report - 2026-11-08T12:30:16Z

Source data: `20261108T122528Z` &nbsp;|&nbsp; Total events analyzed: **656779** &nbsp;|&nbsp; Unique attacker IPs: **6334**

Events by source: `honeypots`: 44745, `suricata`: 521368, `p0f`: 90666

_233487 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `45.141.202.113` | 16854 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `80.91.71.147` | 2282 | Türkiye | Istanbul | Hostlayici Internet ve Bilisim Hizmetleri |
| `109.160.32.171` | 1474 | The Netherlands | Amsterdam | GBTCloud |
| `77.91.71.90` | 1398 | Israel | Tel Aviv | NEW |
| `77.237.239.31` | 1375 | France | Lauterbourg | Contabo GmbH |
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

## Top Countries
| Country | Events |
|---|---:|
| The Netherlands | 24105 |
| United States | 15995 |
| Mauritius | 12732 |
| China | 5853 |
| Israel | 4377 |
| France | 3303 |
| Kazakhstan | 2939 |
| Germany | 2619 |
| Türkiye | 2340 |
| Singapore | 1346 |
| Hong Kong | 1041 |
| United Kingdom | 990 |
| Poland | 896 |
| India | 762 |
| Belgium | 760 |
| Sweden | 728 |
| Thailand | 564 |
| Hungary | 556 |
| Japan | 526 |
| Canada | 499 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 38609 |
| 80 | 25411 |
| 443 | 23552 |
| 64295 | 47 |
| 37208 | 7 |
| 57642 | 2 |
| 58424 | 2 |
| 51254 | 2 |
| 33382 | 2 |
| 60890 | 2 |
| 55764 | 2 |
| 42258 | 2 |
| 38750 | 2 |
| 34048 | 2 |
| 46828 | 2 |
| 40688 | 2 |
| 37174 | 2 |
| 58618 | 2 |
| 36980 | 2 |
| 43596 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `196.20.216.206` | 5778 |
| `106.38.51.68` | 1286 |
| `109.160.32.171` | 679 |
| `43.128.101.247` | 381 |
| `135.148.217.213` | 381 |
| `47.113.193.48` | 266 |
| `83.168.110.251` | 253 |
| `47.251.165.65` | 151 |
| `91.218.108.6` | 104 |
| `109.160.32.123` | 64 |
| `118.70.239.231` | 62 |
| `103.72.57.129` | 45 |
| `77.91.71.90` | 39 |
| `8.217.68.84` | 32 |
| `223.243.179.70` | 31 |
| `121.227.31.82` | 31 |
| `113.98.254.50` | 31 |
| `4.4.66.84` | 31 |
| `103.243.25.44` | 31 |
| `60.165.119.59` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 6

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 76 |
| `140.248.150.49` | 62 |
| `146.75.30.49` | 24 |
| `67.202.15.124` | 8 |
| `54.224.99.219` | 6 |
| `54.234.187.186` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 23 |
| `root` | `admin` | 19 |
| `root` | `ubuntu` | 18 |
| `root` | `password` | 18 |
| `root` | `passwd` | 18 |
| `root` | `qwerty` | 18 |
| `root` | `linux` | 17 |
| `root` | `apache` | 17 |
| `root` | `root` | 17 |
| `root` | `nginx` | 16 |
| `root` | `mysql` | 16 |
| `root` | `docker` | 16 |
| `root` | `vps` | 16 |
| `root` | `host` | 16 |
| `root` | `web` | 16 |
| `root` | `pass` | 16 |
| `root` | `guest` | 16 |
| `root` | `centos` | 15 |
| `root` | `www` | 15 |
| `root` | `default` | 15 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-09 | 4172 |
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
| 2026-11-05 | 1280 |
| 2026-11-06 | 2394 |
| 2026-11-07 | 817 |
| 2026-11-08 | 661 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._