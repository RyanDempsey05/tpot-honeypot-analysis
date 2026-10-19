# T-Pot Honeypot Report - 2026-10-19T11:36:20Z

Source data: `20261019T113128Z` &nbsp;|&nbsp; Total events analyzed: **452988** &nbsp;|&nbsp; Unique attacker IPs: **6747**

Events by source: `honeypots`: 54743, `suricata`: 337257, `p0f`: 60988

_231227 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `77.91.71.90` | 1642 | Israel | Tel Aviv | NEW |
| `45.148.10.9` | 1218 | The Netherlands | Amsterdam | Techoff SRV Limited |
| `77.239.124.36` | 1146 | France | Paris | RocketCloud |
| `135.148.217.213` | 1021 | United States | Warrenton | Cyera |
| `190.119.63.81` | 1008 | Peru | Lima | America Movil Peru S.A.C |
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
| `74.207.252.24` | 690 | United States | Fremont | Linode |
| `45.198.224.124` | 627 | Sweden | Stockholm | Vpsvault.host LTD |
| `185.218.86.25` | 572 | Hong Kong | Sheung Wan | TC DATACENTER LIMITED |
| `83.168.110.251` | 522 | Poland | Warsaw | SkyPass Solutions Sp. z.o.o |
| `77.239.124.206` | 476 | France | Paris | RocketCloud |
| `91.92.47.87` | 443 | The Netherlands | Amsterdam | TechTies Inc |
| `165.154.137.186` | 389 | Vietnam | Ho Chi Minh City | Ucloud Information Technology (hk) Limited |
| `137.23.38.53` | 321 | India | Mumbai | Oracle Cloud Infrastructure (ap-mumbai-1) |
| `94.154.43.250` | 320 | The Netherlands | Amsterdam | FOP Danik Vyacheslav Evgenievich |
| `35.230.81.28` | 257 | United States | The Dalles | Google Cloud (us-west1) |
| `209.15.114.109` | 256 | Thailand | Vadhana | catCloud |

## Top Countries
| Country | Events |
|---|---:|
| United States | 16068 |
| Mauritius | 12734 |
| France | 6760 |
| The Netherlands | 5445 |
| China | 4953 |
| Germany | 2758 |
| United Kingdom | 1885 |
| Israel | 1722 |
| Hong Kong | 1368 |
| Belgium | 1303 |
| Singapore | 1135 |
| Peru | 1009 |
| Sweden | 1001 |
| India | 908 |
| Canada | 869 |
| Brazil | 842 |
| Poland | 611 |
| Thailand | 565 |
| Vietnam | 520 |
| Japan | 512 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 32243 |
| 80 | 20976 |
| 443 | 14373 |
| 64295 | 39 |
| 50296 | 7 |
| 40692 | 7 |
| 58218 | 2 |
| 35072 | 2 |
| 51106 | 2 |
| 49914 | 2 |
| 39190 | 2 |
| 60842 | 2 |
| 60332 | 2 |
| 41128 | 2 |
| 40688 | 2 |
| 37174 | 2 |
| 42258 | 2 |
| 37928 | 2 |
| 53388 | 2 |
| 58618 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `196.20.216.206` | 5778 |
| `106.38.51.68` | 1286 |
| `77.239.124.36` | 513 |
| `135.148.217.213` | 499 |
| `190.119.63.81` | 496 |
| `83.168.110.251` | 253 |
| `165.154.137.186` | 185 |
| `77.239.124.206` | 179 |
| `91.218.108.6` | 104 |
| `20.235.157.149` | 100 |
| `47.251.70.129` | 100 |
| `47.242.67.96` | 95 |
| `39.106.217.151` | 94 |
| `50.6.227.30` | 80 |
| `77.239.124.149` | 76 |
| `77.91.71.90` | 55 |
| `123.139.242.2` | 47 |
| `77.239.124.61` | 46 |
| `51.75.200.186` | 35 |
| `154.211.13.102` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 5

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 107 |
| `140.248.150.49` | 64 |
| `146.75.30.49` | 33 |
| `54.224.99.219` | 5 |
| `100.25.103.9` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 30 |
| `root` | `root` | 27 |
| `root` | `password` | 25 |
| `root` | `admin` | 24 |
| `root` | `passwd` | 18 |
| `root` | `guest` | 17 |
| `root` | `ubuntu` | 16 |
| `root` | `pass` | 16 |
| `root` | `qwerty` | 16 |
| `root` | `default` | 15 |
| `root` | `temp` | 15 |
| `root` | `system` | 15 |
| `root` | `sys` | 15 |
| `root` | `sysadmin` | 15 |
| `root` | `super` | 15 |
| `root` | `linux` | 14 |
| `root` | `vps` | 14 |
| `root` | `administrator` | 14 |
| `root` | `portfolio` | 14 |
| `root` | `temponly` | 14 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-09-19 | 1282 |
| 2026-09-20 | 2554 |
| 2026-09-21 | 1441 |
| 2026-09-22 | 1172 |
| 2026-09-23 | 2039 |
| 2026-09-24 | 1080 |
| 2026-09-25 | 1743 |
| 2026-09-26 | 2297 |
| 2026-09-27 | 1152 |
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
| 2026-10-19 | 739 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._