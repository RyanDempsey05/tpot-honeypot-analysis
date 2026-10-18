# T-Pot Honeypot Report - 2026-10-18T10:09:30Z

Source data: `20261018T100435Z` &nbsp;|&nbsp; Total events analyzed: **453210** &nbsp;|&nbsp; Unique attacker IPs: **6730**

Events by source: `honeypots`: 55433, `suricata`: 336488, `p0f`: 61289

_230813 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

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
| `77.239.124.172` | 692 | France | Paris | RocketCloud |
| `74.207.252.24` | 690 | United States | Fremont | Linode |
| `185.218.86.25` | 589 | Hong Kong | Sheung Wan | TC DATACENTER LIMITED |
| `45.198.224.124` | 586 | Sweden | Stockholm | Vpsvault.host LTD |
| `83.168.110.251` | 522 | Poland | Warsaw | SkyPass Solutions Sp. z.o.o |
| `77.239.124.206` | 476 | France | Paris | RocketCloud |
| `91.92.47.87` | 443 | The Netherlands | Amsterdam | TechTies Inc |
| `165.154.137.186` | 389 | Vietnam | Ho Chi Minh City | Ucloud Information Technology (hk) Limited |
| `137.23.38.53` | 321 | India | Mumbai | Oracle Cloud Infrastructure (ap-mumbai-1) |
| `94.154.43.250` | 314 | The Netherlands | Amsterdam | FOP Danik Vyacheslav Evgenievich |
| `35.230.81.28` | 257 | United States | The Dalles | Google Cloud (us-west1) |

## Top Countries
| Country | Events |
|---|---:|
| United States | 16229 |
| Mauritius | 12734 |
| France | 7438 |
| The Netherlands | 5449 |
| China | 4938 |
| Germany | 2706 |
| United Kingdom | 1861 |
| Israel | 1720 |
| Hong Kong | 1336 |
| Belgium | 1282 |
| Singapore | 1138 |
| Peru | 1009 |
| Sweden | 940 |
| Brazil | 913 |
| India | 909 |
| Canada | 855 |
| Poland | 611 |
| Thailand | 565 |
| Vietnam | 524 |
| Japan | 504 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 33056 |
| 80 | 20940 |
| 443 | 14259 |
| 64295 | 39 |
| 40692 | 7 |
| 50296 | 7 |
| 35072 | 2 |
| 36356 | 2 |
| 49914 | 2 |
| 39950 | 2 |
| 37928 | 2 |
| 55072 | 2 |
| 58618 | 2 |
| 42258 | 2 |
| 42246 | 2 |
| 57058 | 2 |
| 51106 | 2 |
| 53300 | 2 |
| 40688 | 2 |
| 37174 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `196.20.216.206` | 5778 |
| `106.38.51.68` | 1286 |
| `77.239.124.36` | 513 |
| `135.148.217.213` | 499 |
| `190.119.63.81` | 496 |
| `77.239.124.172` | 300 |
| `83.168.110.251` | 253 |
| `165.154.137.186` | 185 |
| `77.239.124.206` | 179 |
| `91.218.108.6` | 104 |
| `166.248.3.175` | 100 |
| `47.251.70.129` | 100 |
| `20.235.157.149` | 100 |
| `47.242.67.96` | 95 |
| `39.106.217.151` | 94 |
| `50.6.227.30` | 80 |
| `77.239.124.149` | 76 |
| `77.91.71.90` | 55 |
| `123.139.242.2` | 47 |
| `77.239.124.61` | 46 |

**Likely port-scan sources** (>= 5 distinct ports touched): 5

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 89 |
| `140.248.150.49` | 57 |
| `146.75.30.49` | 33 |
| `100.25.103.9` | 5 |
| `54.224.99.219` | 5 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 29 |
| `root` | `root` | 27 |
| `root` | `password` | 25 |
| `root` | `admin` | 22 |
| `root` | `passwd` | 17 |
| `root` | `pass` | 15 |
| `root` | `guest` | 15 |
| `pi` | `raspberry` | 15 |
| `root` | `ubuntu` | 15 |
| `user` | `user` | 15 |
| `root` | `linux` | 14 |
| `root` | `default` | 14 |
| `root` | `temp` | 14 |
| `root` | `system` | 14 |
| `root` | `qwerty` | 14 |
| `root` | `vps` | 13 |
| `root` | `administrator` | 13 |
| `root` | `sys` | 13 |
| `root` | `sysadmin` | 13 |
| `root` | `super` | 13 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-09-18 | 1620 |
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
| 2026-10-12 | 2661 |
| 2026-10-13 | 1690 |
| 2026-10-14 | 1412 |
| 2026-10-15 | 1146 |
| 2026-10-16 | 1221 |
| 2026-10-17 | 1851 |
| 2026-10-18 | 438 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._