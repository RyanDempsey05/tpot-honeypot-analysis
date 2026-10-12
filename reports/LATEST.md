# T-Pot Honeypot Report - 2026-10-12T13:55:34Z

Source data: `20261012T135043Z` &nbsp;|&nbsp; Total events analyzed: **440087** &nbsp;|&nbsp; Unique attacker IPs: **6693**

Events by source: `honeypots`: 57061, `suricata`: 331721, `p0f`: 51305

_232589 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `77.91.71.90` | 1416 | Israel | Tel Aviv | NEW |
| `45.148.10.9` | 1218 | The Netherlands | Amsterdam | Techoff SRV Limited |
| `77.239.124.36` | 1146 | France | Paris | RocketCloud |
| `94.237.82.187` | 1058 | Germany | Frankfurt am Main |  |
| `190.119.63.81` | 1008 | Peru | Lima | America Movil Peru S.A.C |
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
| `185.218.86.25` | 713 | Hong Kong | Sheung Wan | TC DATACENTER LIMITED |
| `79.29.9.2` | 706 | Italy | Rome | NAS DHCP Pool TORINO |
| `77.239.124.172` | 692 | France | Paris | RocketCloud |
| `74.207.252.24` | 690 | United States | Fremont | Linode |
| `77.239.124.206` | 476 | France | Paris | RocketCloud |
| `91.92.47.87` | 443 | The Netherlands | Amsterdam | TechTies Inc |
| `195.177.94.103` | 414 | France | Marseille | Pitline Ltd |
| `165.154.137.186` | 389 | Vietnam | Ho Chi Minh City | Ucloud Information Technology (hk) Limited |
| `45.198.224.124` | 344 | Sweden | Stockholm | Vpsvault.host LTD |
| `16.5.0.236` | 341 | Brazil | São Paulo | EMBNEX. LLC |
| `160.30.132.209` | 339 | Nepal | Kathmandu | Islington College Pvt. Ltd |

## Top Countries
| Country | Events |
|---|---:|
| United States | 15146 |
| Mauritius | 12734 |
| France | 7553 |
| The Netherlands | 5554 |
| China | 5187 |
| Germany | 3372 |
| United Kingdom | 1767 |
| Singapore | 1704 |
| Hong Kong | 1632 |
| Israel | 1487 |
| Brazil | 1139 |
| Belgium | 1053 |
| Peru | 1011 |
| Nepal | 923 |
| Italy | 765 |
| Canada | 718 |
| Sweden | 646 |
| India | 620 |
| Vietnam | 538 |
| Japan | 510 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 33865 |
| 80 | 20594 |
| 443 | 14859 |
| 64295 | 44 |
| 40692 | 7 |
| 50296 | 7 |
| 58618 | 2 |
| 36366 | 2 |
| 42246 | 2 |
| 55930 | 2 |
| 58752 | 2 |
| 41028 | 2 |
| 58084 | 2 |
| 33634 | 2 |
| 47132 | 2 |
| 60332 | 2 |
| 41128 | 2 |
| 49914 | 2 |
| 51106 | 2 |
| 39950 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `196.20.216.206` | 5778 |
| `106.38.51.68` | 1286 |
| `77.239.124.36` | 513 |
| `190.119.63.81` | 496 |
| `79.29.9.2` | 341 |
| `77.239.124.172` | 300 |
| `165.154.137.186` | 185 |
| `77.239.124.206` | 179 |
| `160.30.132.209` | 163 |
| `135.148.217.213` | 118 |
| `91.218.108.6` | 104 |
| `43.161.249.223` | 100 |
| `20.235.157.149` | 100 |
| `166.248.3.175` | 100 |
| `47.251.70.129` | 100 |
| `47.242.67.96` | 95 |
| `39.106.217.151` | 94 |
| `115.85.243.22` | 82 |
| `50.6.227.30` | 80 |
| `77.239.124.149` | 76 |

**Likely port-scan sources** (>= 5 distinct ports touched): 4

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 100 |
| `140.248.150.49` | 60 |
| `146.75.30.49` | 36 |
| `54.224.99.219` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 36 |
| `root` | `root` | 29 |
| `root` | `password` | 27 |
| `root` | `admin` | 22 |
| `user` | `user` | 18 |
| `root` | `ubuntu` | 15 |
| `root` | `passwd` | 15 |
| `root` | `qwerty` | 15 |
| `root` | `test` | 14 |
| `pi` | `raspberry` | 14 |
| `root` | `linux` | 13 |
| `root` | `pass` | 13 |
| `root` | `guest` | 13 |
| `root` | `1234567890` | 13 |
| `deploy` | `deploy` | 13 |
| `root` | `abcd1234` | 13 |
| `test` | `test123` | 13 |
| `admin` | `admin123` | 13 |
| `ubuntu` | `123456` | 13 |
| `admin` | `admin` | 13 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-09-12 | 912 |
| 2026-09-13 | 874 |
| 2026-09-14 | 1824 |
| 2026-09-15 | 3325 |
| 2026-09-16 | 1063 |
| 2026-09-17 | 2219 |
| 2026-09-18 | 1897 |
| 2026-09-19 | 1629 |
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
| 2026-10-12 | 1002 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._