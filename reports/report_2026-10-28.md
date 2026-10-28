# T-Pot Honeypot Report - 2026-10-28T11:54:06Z

Source data: `20261028T114914Z` &nbsp;|&nbsp; Total events analyzed: **477242** &nbsp;|&nbsp; Unique attacker IPs: **6589**

Events by source: `honeypots`: 52411, `suricata`: 349247, `p0f`: 75584

_233301 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `77.91.71.90` | 1915 | Israel | Tel Aviv | NEW |
| `45.148.10.9` | 1218 | The Netherlands | Amsterdam | Techoff SRV Limited |
| `77.239.124.36` | 1146 | France | Paris | RocketCloud |
| `135.148.217.213` | 1021 | United States | Warrenton | Cyera |
| `43.128.101.247` | 769 | Singapore | Singapore | Tencent Cloud Computing |
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
| `77.237.239.31` | 753 | France | Lauterbourg | Contabo GmbH |
| `45.198.224.124` | 655 | Sweden | Stockholm | Vpsvault.host LTD |
| `83.168.110.251` | 522 | Poland | Warsaw | SkyPass Solutions Sp. z.o.o |
| `77.239.124.206` | 476 | France | Paris | RocketCloud |
| `91.92.47.87` | 443 | The Netherlands | Amsterdam | TechTies Inc |
| `165.154.137.186` | 389 | Vietnam | Ho Chi Minh City | Ucloud Information Technology (hk) Limited |
| `137.23.38.53` | 321 | India | Mumbai | Oracle Cloud Infrastructure (ap-mumbai-1) |
| `94.154.43.250` | 320 | The Netherlands | Amsterdam | FOP Danik Vyacheslav Evgenievich |
| `185.218.86.25` | 302 | Hong Kong | Sheung Wan | TC DATACENTER LIMITED |
| `138.226.239.91` | 301 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `138.226.239.90` | 291 | The Netherlands | Amsterdam | Vlad Cojuhari |

## Top Countries
| Country | Events |
|---|---:|
| United States | 14987 |
| Mauritius | 12734 |
| France | 7396 |
| The Netherlands | 6611 |
| China | 5432 |
| Israel | 3200 |
| Germany | 2683 |
| Singapore | 1713 |
| Kazakhstan | 1255 |
| United Kingdom | 1082 |
| Belgium | 968 |
| Sweden | 943 |
| India | 926 |
| Hong Kong | 802 |
| Poland | 624 |
| Canada | 565 |
| Brazil | 564 |
| Thailand | 554 |
| Bulgaria | 524 |
| Vietnam | 524 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 35127 |
| 80 | 21287 |
| 443 | 12498 |
| 64295 | 45 |
| 40692 | 7 |
| 36980 | 2 |
| 43596 | 2 |
| 60332 | 2 |
| 41128 | 2 |
| 35072 | 2 |
| 57058 | 2 |
| 60890 | 2 |
| 38630 | 2 |
| 33634 | 2 |
| 47132 | 2 |
| 40688 | 2 |
| 37174 | 2 |
| 42258 | 2 |
| 33382 | 2 |
| 58218 | 2 |

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
| `77.239.124.149` | 76 |
| `77.91.71.90` | 65 |
| `109.160.32.123` | 64 |
| `123.139.242.2` | 47 |
| `77.239.124.61` | 46 |
| `51.75.200.186` | 35 |
| `49.12.249.111` | 31 |
| `213.215.209.101` | 31 |
| `103.243.25.44` | 31 |
| `121.227.31.82` | 31 |
| `223.243.179.70` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 6

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 102 |
| `140.248.150.49` | 74 |
| `146.75.30.49` | 29 |
| `54.173.240.110` | 6 |
| `54.224.99.219` | 6 |
| `67.202.15.124` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 30 |
| `root` | `password` | 27 |
| `root` | `root` | 26 |
| `root` | `admin` | 25 |
| `root` | `passwd` | 21 |
| `root` | `ubuntu` | 20 |
| `root` | `pass` | 20 |
| `root` | `guest` | 20 |
| `root` | `linux` | 19 |
| `root` | `vps` | 19 |
| `root` | `default` | 19 |
| `root` | `temp` | 19 |
| `root` | `system` | 19 |
| `root` | `sys` | 19 |
| `root` | `sysadmin` | 19 |
| `root` | `super` | 19 |
| `root` | `qwerty` | 19 |
| `root` | `apache` | 18 |
| `root` | `host` | 18 |
| `root` | `administrator` | 18 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-09-28 | 1199 |
| 2026-09-29 | 1049 |
| 2026-09-30 | 2514 |
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
| 2026-10-28 | 868 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._