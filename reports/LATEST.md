# T-Pot Honeypot Report - 2026-10-25T10:26:41Z

Source data: `20261025T102154Z` &nbsp;|&nbsp; Total events analyzed: **461440** &nbsp;|&nbsp; Unique attacker IPs: **6657**

Events by source: `honeypots`: 52559, `suricata`: 343573, `p0f`: 65308

_231840 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `77.91.71.90` | 1767 | Israel | Tel Aviv | NEW |
| `45.148.10.9` | 1218 | The Netherlands | Amsterdam | Techoff SRV Limited |
| `77.239.124.36` | 1146 | France | Paris | RocketCloud |
| `135.148.217.213` | 1021 | United States | Warrenton | Cyera |
| `43.128.101.247` | 769 | Singapore | Singapore | Tencent Cloud Computing |
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
| `45.198.224.124` | 655 | Sweden | Stockholm | Vpsvault.host LTD |
| `83.168.110.251` | 522 | Poland | Warsaw | SkyPass Solutions Sp. z.o.o |
| `190.119.63.81` | 501 | Peru | Lima | America Movil Peru S.A.C |
| `77.239.124.206` | 476 | France | Paris | RocketCloud |
| `91.92.47.87` | 443 | The Netherlands | Amsterdam | TechTies Inc |
| `185.218.86.25` | 405 | Hong Kong | Sheung Wan | TC DATACENTER LIMITED |
| `165.154.137.186` | 389 | Vietnam | Ho Chi Minh City | Ucloud Information Technology (hk) Limited |
| `137.23.38.53` | 321 | India | Mumbai | Oracle Cloud Infrastructure (ap-mumbai-1) |
| `94.154.43.250` | 320 | The Netherlands | Amsterdam | FOP Danik Vyacheslav Evgenievich |
| `109.160.32.123` | 263 | The Netherlands | Amsterdam | GBTCloud |
| `35.230.81.28` | 257 | United States | The Dalles | Google Cloud (us-west1) |

## Top Countries
| Country | Events |
|---|---:|
| United States | 15273 |
| Mauritius | 12734 |
| France | 6660 |
| The Netherlands | 6322 |
| China | 4749 |
| Germany | 2603 |
| Israel | 2351 |
| Singapore | 2054 |
| United Kingdom | 1136 |
| Hong Kong | 1110 |
| Belgium | 1094 |
| India | 947 |
| Sweden | 920 |
| Canada | 782 |
| Brazil | 631 |
| Poland | 596 |
| Kazakhstan | 563 |
| Thailand | 555 |
| Japan | 541 |
| Vietnam | 531 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 34056 |
| 80 | 20072 |
| 443 | 13278 |
| 64295 | 43 |
| 40692 | 7 |
| 35072 | 2 |
| 45508 | 2 |
| 45052 | 2 |
| 42258 | 2 |
| 51254 | 2 |
| 39950 | 2 |
| 36366 | 2 |
| 40688 | 2 |
| 37174 | 2 |
| 58618 | 2 |
| 60890 | 2 |
| 51106 | 2 |
| 57058 | 2 |
| 58218 | 2 |
| 37928 | 2 |

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
| `190.119.63.81` | 248 |
| `165.154.137.186` | 185 |
| `77.239.124.206` | 179 |
| `91.218.108.6` | 104 |
| `47.251.70.129` | 100 |
| `47.242.67.96` | 95 |
| `77.239.124.149` | 76 |
| `109.160.32.123` | 64 |
| `77.91.71.90` | 58 |
| `123.139.242.2` | 47 |
| `77.239.124.61` | 46 |
| `51.75.200.186` | 35 |
| `180.76.147.239` | 31 |
| `154.211.13.102` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 4

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 123 |
| `140.248.150.49` | 72 |
| `146.75.30.49` | 32 |
| `54.173.240.110` | 5 |

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
| `root` | `passwd` | 19 |
| `root` | `ubuntu` | 18 |
| `root` | `pass` | 17 |
| `root` | `guest` | 17 |
| `root` | `qwerty` | 17 |
| `root` | `linux` | 16 |
| `root` | `vps` | 16 |
| `root` | `default` | 16 |
| `root` | `temp` | 16 |
| `root` | `system` | 16 |
| `root` | `sys` | 16 |
| `root` | `sysadmin` | 16 |
| `root` | `super` | 16 |
| `root` | `apache` | 15 |
| `root` | `host` | 15 |
| `root` | `administrator` | 15 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-09-25 | 1438 |
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
| 2026-10-19 | 1172 |
| 2026-10-20 | 1022 |
| 2026-10-21 | 1233 |
| 2026-10-22 | 1869 |
| 2026-10-23 | 2357 |
| 2026-10-24 | 1794 |
| 2026-10-25 | 997 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._