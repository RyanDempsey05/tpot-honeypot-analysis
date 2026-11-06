# T-Pot Honeypot Report - 2026-11-06T13:30:45Z

Source data: `20261106T132553Z` &nbsp;|&nbsp; Total events analyzed: **667364** &nbsp;|&nbsp; Unique attacker IPs: **6385**

Events by source: `honeypots`: 50489, `suricata`: 526445, `p0f`: 90430

_240664 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `45.141.202.113` | 16854 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `80.91.71.147` | 2282 | Türkiye | Istanbul | Hostlayici Internet ve Bilisim Hizmetleri |
| `77.91.71.90` | 1736 | Israel | Tel Aviv | NEW |
| `77.237.239.31` | 1375 | France | Lauterbourg | Contabo GmbH |
| `135.148.217.213` | 771 | United States | New York | Cyera |
| `43.128.101.247` | 769 | Singapore | Singapore | Tencent Cloud Computing |
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
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

## Top Countries
| Country | Events |
|---|---:|
| The Netherlands | 22648 |
| United States | 16561 |
| Mauritius | 12732 |
| France | 5926 |
| China | 5760 |
| Israel | 4713 |
| Kazakhstan | 2947 |
| Germany | 2630 |
| Türkiye | 2329 |
| Singapore | 1586 |
| Hong Kong | 1065 |
| United Kingdom | 940 |
| Poland | 890 |
| Sweden | 808 |
| Unknown | 801 |
| Belgium | 741 |
| India | 741 |
| Japan | 572 |
| Hungary | 560 |
| Thailand | 553 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 37521 |
| 80 | 28802 |
| 443 | 24192 |
| 64295 | 48 |
| 40692 | 7 |
| 37208 | 7 |
| 43596 | 2 |
| 36572 | 2 |
| 56322 | 2 |
| 33382 | 2 |
| 39950 | 2 |
| 60332 | 2 |
| 41128 | 2 |
| 40688 | 2 |
| 37174 | 2 |
| 57642 | 2 |
| 36980 | 2 |
| 48486 | 2 |
| 42258 | 2 |
| 60890 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `196.20.216.206` | 5778 |
| `106.38.51.68` | 1286 |
| `135.148.217.213` | 381 |
| `43.128.101.247` | 381 |
| `47.113.193.48` | 266 |
| `83.168.110.251` | 253 |
| `47.251.165.65` | 151 |
| `91.218.108.6` | 104 |
| `109.160.32.123` | 64 |
| `118.70.239.231` | 62 |
| `77.91.71.90` | 50 |
| `103.72.57.129` | 45 |
| `8.217.68.84` | 32 |
| `154.211.13.102` | 31 |
| `42.101.60.58` | 31 |
| `50.114.172.201` | 31 |
| `103.243.25.44` | 31 |
| `120.71.148.144` | 31 |
| `121.227.31.82` | 31 |
| `223.243.179.70` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 5

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 74 |
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
| `root` | `123456` | 22 |
| `root` | `ubuntu` | 20 |
| `root` | `admin` | 19 |
| `root` | `linux` | 18 |
| `root` | `apache` | 18 |
| `root` | `password` | 18 |
| `root` | `passwd` | 18 |
| `root` | `root` | 18 |
| `root` | `qwerty` | 18 |
| `root` | `centos` | 17 |
| `root` | `nginx` | 17 |
| `root` | `mysql` | 17 |
| `root` | `docker` | 17 |
| `root` | `vps` | 17 |
| `root` | `host` | 17 |
| `root` | `web` | 17 |
| `root` | `guest` | 17 |
| `root` | `debian` | 16 |
| `root` | `www` | 16 |
| `root` | `default` | 16 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-07 | 4828 |
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
| 2026-11-05 | 1280 |
| 2026-11-06 | 572 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._