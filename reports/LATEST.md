# T-Pot Honeypot Report - 2026-10-21T10:53:06Z

Source data: `20261021T104813Z` &nbsp;|&nbsp; Total events analyzed: **455024** &nbsp;|&nbsp; Unique attacker IPs: **6715**

Events by source: `honeypots`: 52722, `suricata`: 339341, `p0f`: 62961

_231380 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

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
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
| `45.198.224.124` | 645 | Sweden | Stockholm | Vpsvault.host LTD |
| `83.168.110.251` | 522 | Poland | Warsaw | SkyPass Solutions Sp. z.o.o |
| `185.218.86.25` | 520 | Hong Kong | Sheung Wan | TC DATACENTER LIMITED |
| `190.119.63.81` | 501 | Peru | Lima | America Movil Peru S.A.C |
| `77.239.124.206` | 476 | France | Paris | RocketCloud |
| `91.92.47.87` | 443 | The Netherlands | Amsterdam | TechTies Inc |
| `165.154.137.186` | 389 | Vietnam | Ho Chi Minh City | Ucloud Information Technology (hk) Limited |
| `137.23.38.53` | 321 | India | Mumbai | Oracle Cloud Infrastructure (ap-mumbai-1) |
| `94.154.43.250` | 320 | The Netherlands | Amsterdam | FOP Danik Vyacheslav Evgenievich |
| `109.160.32.123` | 263 | The Netherlands | Amsterdam | GBTCloud |
| `35.230.81.28` | 257 | United States | The Dalles | Google Cloud (us-west1) |
| `203.188.11.114` | 256 | Thailand | Khwaeng Thung Song Hong | KSC Commercial Internet Co.Ltd |

## Top Countries
| Country | Events |
|---|---:|
| United States | 14950 |
| Mauritius | 12734 |
| France | 6813 |
| The Netherlands | 5737 |
| China | 4891 |
| Germany | 2785 |
| United Kingdom | 1895 |
| Israel | 1713 |
| Hong Kong | 1329 |
| Singapore | 1232 |
| Belgium | 1230 |
| Sweden | 1026 |
| Canada | 841 |
| Brazil | 704 |
| India | 691 |
| Poland | 596 |
| Thailand | 554 |
| Japan | 537 |
| Vietnam | 529 |
| Peru | 502 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 31774 |
| 80 | 20094 |
| 443 | 13897 |
| 64295 | 40 |
| 40692 | 7 |
| 50296 | 7 |
| 39950 | 2 |
| 60332 | 2 |
| 41128 | 2 |
| 47114 | 2 |
| 55072 | 2 |
| 60890 | 2 |
| 55764 | 2 |
| 42246 | 2 |
| 40688 | 2 |
| 37174 | 2 |
| 57058 | 2 |
| 45508 | 2 |
| 45052 | 2 |
| 37928 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `196.20.216.206` | 5778 |
| `106.38.51.68` | 1286 |
| `77.239.124.36` | 513 |
| `135.148.217.213` | 499 |
| `83.168.110.251` | 253 |
| `190.119.63.81` | 248 |
| `165.154.137.186` | 185 |
| `77.239.124.206` | 179 |
| `91.218.108.6` | 104 |
| `47.251.70.129` | 100 |
| `47.242.67.96` | 95 |
| `39.106.217.151` | 94 |
| `50.6.227.30` | 80 |
| `77.239.124.149` | 76 |
| `109.160.32.123` | 64 |
| `77.91.71.90` | 55 |
| `123.139.242.2` | 47 |
| `77.239.124.61` | 46 |
| `51.75.200.186` | 35 |
| `180.76.147.239` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 5

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 100 |
| `140.248.150.49` | 56 |
| `146.75.30.49` | 28 |
| `54.224.99.219` | 5 |
| `100.25.103.9` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 29 |
| `root` | `password` | 24 |
| `root` | `root` | 24 |
| `root` | `admin` | 22 |
| `root` | `passwd` | 17 |
| `root` | `ubuntu` | 16 |
| `root` | `pass` | 16 |
| `root` | `guest` | 16 |
| `root` | `default` | 15 |
| `root` | `temp` | 15 |
| `root` | `system` | 15 |
| `root` | `sys` | 15 |
| `root` | `sysadmin` | 15 |
| `root` | `super` | 15 |
| `root` | `qwerty` | 15 |
| `root` | `linux` | 14 |
| `root` | `vps` | 14 |
| `root` | `administrator` | 14 |
| `root` | `portfolio` | 14 |
| `root` | `temponly` | 14 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-09-21 | 1211 |
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
| 2026-10-19 | 1172 |
| 2026-10-20 | 1022 |
| 2026-10-21 | 763 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._