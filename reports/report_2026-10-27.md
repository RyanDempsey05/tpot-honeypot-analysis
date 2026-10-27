# T-Pot Honeypot Report - 2026-10-27T11:19:32Z

Source data: `20261027T111440Z` &nbsp;|&nbsp; Total events analyzed: **465727** &nbsp;|&nbsp; Unique attacker IPs: **6595**

Events by source: `honeypots`: 52233, `suricata`: 347146, `p0f`: 66348

_232803 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `77.91.71.90` | 1867 | Israel | Tel Aviv | NEW |
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
| `185.218.86.25` | 336 | Hong Kong | Sheung Wan | TC DATACENTER LIMITED |
| `137.23.38.53` | 321 | India | Mumbai | Oracle Cloud Infrastructure (ap-mumbai-1) |
| `94.154.43.250` | 320 | The Netherlands | Amsterdam | FOP Danik Vyacheslav Evgenievich |
| `68.209.56.42` | 274 | Netherlands | Halfweg | ServerMania Inc |
| `109.160.32.123` | 263 | The Netherlands | Amsterdam | GBTCloud |

## Top Countries
| Country | Events |
|---|---:|
| United States | 14971 |
| Mauritius | 12734 |
| France | 7390 |
| The Netherlands | 6524 |
| China | 5438 |
| Israel | 2927 |
| Germany | 2587 |
| Singapore | 1712 |
| United Kingdom | 1117 |
| Kazakhstan | 1028 |
| Belgium | 955 |
| Sweden | 936 |
| India | 930 |
| Hong Kong | 833 |
| Poland | 596 |
| Brazil | 595 |
| Canada | 585 |
| Thailand | 552 |
| Japan | 537 |
| Vietnam | 524 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 34329 |
| 80 | 21297 |
| 443 | 12544 |
| 64295 | 44 |
| 40692 | 7 |
| 58424 | 2 |
| 53388 | 2 |
| 51254 | 2 |
| 58218 | 2 |
| 35072 | 2 |
| 42258 | 2 |
| 55764 | 2 |
| 33382 | 2 |
| 36366 | 2 |
| 56322 | 2 |
| 51106 | 2 |
| 40688 | 2 |
| 37174 | 2 |
| 43596 | 2 |
| 33634 | 2 |

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
| `109.160.32.123` | 64 |
| `77.91.71.90` | 63 |
| `123.139.242.2` | 47 |
| `77.239.124.61` | 46 |
| `51.75.200.186` | 35 |
| `120.71.148.144` | 31 |
| `103.243.25.44` | 31 |
| `180.76.147.239` | 31 |
| `113.98.254.50` | 31 |
| `223.243.179.70` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 5

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 116 |
| `140.248.150.49` | 79 |
| `146.75.30.49` | 31 |
| `54.173.240.110` | 5 |
| `54.224.99.219` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 28 |
| `root` | `password` | 25 |
| `root` | `root` | 24 |
| `root` | `admin` | 23 |
| `root` | `passwd` | 19 |
| `root` | `ubuntu` | 18 |
| `root` | `pass` | 18 |
| `root` | `guest` | 18 |
| `root` | `linux` | 17 |
| `root` | `vps` | 17 |
| `root` | `default` | 17 |
| `root` | `temp` | 17 |
| `root` | `system` | 17 |
| `root` | `sys` | 17 |
| `root` | `sysadmin` | 17 |
| `root` | `super` | 17 |
| `root` | `qwerty` | 17 |
| `root` | `apache` | 16 |
| `root` | `host` | 16 |
| `root` | `administrator` | 16 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-09-27 | 783 |
| 2026-09-28 | 1385 |
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
| 2026-10-27 | 900 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._