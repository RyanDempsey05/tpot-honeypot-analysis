# T-Pot Honeypot Report - 2026-10-30T11:55:22Z

Source data: `20261030T115035Z` &nbsp;|&nbsp; Total events analyzed: **501025** &nbsp;|&nbsp; Unique attacker IPs: **6578**

Events by source: `honeypots`: 55290, `suricata`: 368197, `p0f`: 77538

_235840 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `45.141.202.113` | 4326 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `77.91.71.90` | 2005 | Israel | Tel Aviv | NEW |
| `77.237.239.31` | 1375 | France | Lauterbourg | Contabo GmbH |
| `45.148.10.9` | 1218 | The Netherlands | Amsterdam | Techoff SRV Limited |
| `77.239.124.36` | 1146 | France | Paris | RocketCloud |
| `135.148.217.213` | 1021 | United States | Warrenton | Cyera |
| `43.128.101.247` | 769 | Singapore | Singapore | Tencent Cloud Computing |
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
| `45.198.224.124` | 655 | Sweden | Stockholm | Vpsvault.host LTD |
| `83.168.110.251` | 522 | Poland | Warsaw | SkyPass Solutions Sp. z.o.o |
| `77.239.124.206` | 476 | France | Paris | RocketCloud |
| `91.92.47.87` | 443 | The Netherlands | Amsterdam | TechTies Inc |
| `138.226.239.90` | 389 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `165.154.137.186` | 389 | Vietnam | Ho Chi Minh City | Ucloud Information Technology (hk) Limited |
| `138.226.239.91` | 389 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `77.91.71.91` | 361 | Israel | Tel Aviv | NEW |
| `77.91.71.92` | 359 | Israel | Tel Aviv | NEW |

## Top Countries
| Country | Events |
|---|---:|
| United States | 15406 |
| Mauritius | 12734 |
| The Netherlands | 11075 |
| France | 7799 |
| China | 5438 |
| Israel | 3729 |
| Germany | 2727 |
| Kazakhstan | 1705 |
| Singapore | 1694 |
| Belgium | 1009 |
| United Kingdom | 1009 |
| Sweden | 953 |
| India | 913 |
| Hong Kong | 763 |
| Poland | 628 |
| Vietnam | 592 |
| Thailand | 552 |
| Canada | 547 |
| Bulgaria | 534 |
| Brazil | 509 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 36191 |
| 80 | 26330 |
| 443 | 12442 |
| 64295 | 45 |
| 40692 | 7 |
| 34048 | 2 |
| 37928 | 2 |
| 51254 | 2 |
| 60332 | 2 |
| 41128 | 2 |
| 57058 | 2 |
| 56322 | 2 |
| 58618 | 2 |
| 33634 | 2 |
| 47132 | 2 |
| 36980 | 2 |
| 43596 | 2 |
| 33382 | 2 |
| 51106 | 2 |
| 53388 | 2 |

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
| `77.91.71.90` | 67 |
| `109.160.32.123` | 64 |
| `123.139.242.2` | 47 |
| `77.239.124.61` | 46 |
| `103.72.57.129` | 45 |
| `51.75.200.186` | 35 |
| `60.165.119.59` | 31 |
| `103.243.25.44` | 31 |
| `49.12.249.111` | 31 |
| `213.215.209.101` | 31 |
| `154.211.13.102` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 6

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 97 |
| `140.248.150.49` | 70 |
| `146.75.30.49` | 30 |
| `54.173.240.110` | 6 |
| `54.224.99.219` | 5 |
| `67.202.15.124` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 30 |
| `root` | `password` | 26 |
| `root` | `root` | 25 |
| `root` | `admin` | 24 |
| `root` | `passwd` | 22 |
| `root` | `ubuntu` | 21 |
| `root` | `guest` | 21 |
| `root` | `linux` | 20 |
| `root` | `vps` | 20 |
| `root` | `default` | 20 |
| `root` | `pass` | 20 |
| `root` | `temp` | 20 |
| `root` | `system` | 20 |
| `root` | `sys` | 20 |
| `root` | `sysadmin` | 20 |
| `root` | `super` | 20 |
| `root` | `qwerty` | 20 |
| `root` | `apache` | 19 |
| `root` | `host` | 19 |
| `root` | `administrator` | 19 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-09-30 | 2306 |
| 2026-10-01 | 1943 |
| 2026-10-02 | 2227 |
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
| 2026-10-30 | 979 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._