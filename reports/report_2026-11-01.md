# T-Pot Honeypot Report - 2026-11-01T12:21:11Z

Source data: `20261101T121625Z` &nbsp;|&nbsp; Total events analyzed: **500254** &nbsp;|&nbsp; Unique attacker IPs: **6549**

Events by source: `honeypots`: 50987, `suricata`: 370454, `p0f`: 78813

_233605 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `45.141.202.113` | 4326 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `77.91.71.90` | 2091 | Israel | Tel Aviv | NEW |
| `77.237.239.31` | 1375 | France | Lauterbourg | Contabo GmbH |
| `77.239.124.36` | 1146 | France | Paris | RocketCloud |
| `135.148.217.213` | 1021 | United States | Warrenton | Cyera |
| `43.128.101.247` | 769 | Singapore | Singapore | Tencent Cloud Computing |
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
| `45.198.224.124` | 655 | Sweden | Stockholm | Vpsvault.host LTD |
| `83.168.110.251` | 522 | Poland | Warsaw | SkyPass Solutions Sp. z.o.o |
| `138.226.239.91` | 479 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `138.226.239.90` | 477 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `77.239.124.206` | 476 | France | Paris | RocketCloud |
| `77.91.71.92` | 453 | Israel | Tel Aviv | NEW |
| `77.91.71.91` | 453 | Israel | Tel Aviv | NEW |
| `185.136.15.82` | 418 | Kazakhstan | Almaty | Vlad Cojuhari |
| `185.136.15.111` | 417 | Kazakhstan | Almaty | Vlad Cojuhari |
| `185.136.15.110` | 415 | Kazakhstan | Almaty | Vlad Cojuhari |

## Top Countries
| Country | Events |
|---|---:|
| United States | 15606 |
| Mauritius | 12734 |
| The Netherlands | 9658 |
| France | 7686 |
| China | 5364 |
| Israel | 4279 |
| Germany | 2626 |
| Kazakhstan | 2160 |
| Singapore | 1517 |
| United Kingdom | 964 |
| Sweden | 942 |
| Poland | 886 |
| India | 883 |
| Belgium | 733 |
| Hong Kong | 717 |
| Japan | 703 |
| Vietnam | 598 |
| Bulgaria | 591 |
| Thailand | 551 |
| Brazil | 533 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 37234 |
| 80 | 26192 |
| 443 | 10936 |
| 64295 | 47 |
| 40692 | 7 |
| 55136 | 2 |
| 35072 | 2 |
| 57058 | 2 |
| 58424 | 2 |
| 60890 | 2 |
| 51254 | 2 |
| 37928 | 2 |
| 34048 | 2 |
| 60332 | 2 |
| 41128 | 2 |
| 56322 | 2 |
| 38630 | 2 |
| 51106 | 2 |
| 45508 | 2 |
| 39950 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `196.20.216.206` | 5778 |
| `106.38.51.68` | 1286 |
| `77.239.124.36` | 513 |
| `135.148.217.213` | 499 |
| `43.128.101.247` | 381 |
| `83.168.110.251` | 253 |
| `165.154.137.186` | 185 |
| `77.239.124.206` | 179 |
| `91.218.108.6` | 104 |
| `77.91.71.90` | 69 |
| `109.160.32.123` | 64 |
| `123.139.242.2` | 47 |
| `77.239.124.61` | 46 |
| `103.72.57.129` | 45 |
| `4.4.66.84` | 31 |
| `223.243.179.70` | 31 |
| `103.243.25.44` | 31 |
| `154.211.13.102` | 31 |
| `42.101.60.58` | 31 |
| `121.227.31.82` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 7

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 93 |
| `140.248.150.49` | 72 |
| `146.75.30.49` | 32 |
| `67.202.15.124` | 6 |
| `54.173.240.110` | 5 |
| `54.224.99.219` | 5 |
| `54.234.187.186` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 27 |
| `root` | `password` | 23 |
| `root` | `root` | 23 |
| `root` | `admin` | 22 |
| `root` | `ubuntu` | 21 |
| `root` | `passwd` | 21 |
| `root` | `linux` | 20 |
| `root` | `apache` | 20 |
| `root` | `guest` | 20 |
| `root` | `vps` | 19 |
| `root` | `default` | 19 |
| `root` | `pass` | 19 |
| `root` | `temp` | 19 |
| `root` | `system` | 19 |
| `root` | `sys` | 19 |
| `root` | `sysadmin` | 19 |
| `root` | `super` | 19 |
| `root` | `qwerty` | 19 |
| `root` | `centos` | 18 |
| `root` | `nginx` | 18 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-02 | 1978 |
| 2026-10-03 | 1388 |
| 2026-10-04 | 1132 |
| 2026-10-05 | 1532 |
| 2026-10-06 | 1391 |
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
| 2026-11-01 | 1438 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._