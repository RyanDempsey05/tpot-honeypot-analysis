# T-Pot Honeypot Report - 2026-11-04T13:32:02Z

Source data: `20261104T132720Z` &nbsp;|&nbsp; Total events analyzed: **675229** &nbsp;|&nbsp; Unique attacker IPs: **6390**

Events by source: `honeypots`: 51749, `suricata`: 530929, `p0f`: 92551

_240533 event(s) from allowlisted IPs (`analysis.ignore_ips` in config.yaml) excluded from the metrics below._

## Top Attacking IPs
| IP | Events | Country | City | Org/ASN |
|---|---:|---|---|---|
| `45.141.202.113` | 16854 | The Netherlands | Zoetermeer | RoyaleHosting BV |
| `196.20.216.206` | 12732 | Mauritius | Port Louis |  |
| `185.177.72.38` | 2749 | France | Vélizy-Villacoublay | FBW NETWORKS |
| `106.38.51.68` | 2697 | China | Beijing | Chinanet BJ |
| `80.91.71.147` | 2282 | Türkiye | Istanbul | Hostlayici Internet ve Bilisim Hizmetleri |
| `77.91.71.90` | 1974 | Israel | Tel Aviv | NEW |
| `77.237.239.31` | 1375 | France | Lauterbourg | Contabo GmbH |
| `77.239.124.36` | 1146 | Unknown |  |  |
| `135.148.217.213` | 1021 | United States | New York | Cyera |
| `43.128.101.247` | 769 | Singapore | Singapore | Tencent Cloud Computing |
| `172.234.207.202` | 760 | United States | Chicago | Akamai Technologies, Inc. |
| `45.198.224.124` | 603 | Sweden | Stockholm | Vpsvault.host LTD |
| `138.226.239.91` | 599 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `47.113.193.48` | 591 | China | Shenzhen | Aliyun Computing Co., LTD |
| `77.91.71.91` | 591 | Israel | Tel Aviv | NEW |
| `138.226.239.90` | 569 | The Netherlands | Amsterdam | Vlad Cojuhari |
| `77.91.71.92` | 562 | Israel | Tel Aviv | NEW |
| `185.136.15.111` | 557 | Kazakhstan | Almaty | Vlad Cojuhari |
| `185.136.15.82` | 556 | Kazakhstan | Almaty | Vlad Cojuhari |
| `198.58.117.211` | 554 | United States | Richardson | Linode |

## Top Countries
| Country | Events |
|---|---:|
| The Netherlands | 22486 |
| United States | 16768 |
| Mauritius | 12732 |
| China | 5946 |
| France | 5923 |
| Israel | 4827 |
| Kazakhstan | 2860 |
| Germany | 2590 |
| Türkiye | 2324 |
| Unknown | 1664 |
| Singapore | 1590 |
| Hong Kong | 1011 |
| United Kingdom | 1002 |
| Sweden | 890 |
| Poland | 888 |
| India | 738 |
| Belgium | 724 |
| Japan | 658 |
| Thailand | 554 |
| Canada | 515 |

## Top Targeted Ports
| Port | Events |
|---|---:|
| 22 | 38850 |
| 80 | 28901 |
| 443 | 24199 |
| 64295 | 47 |
| 40692 | 7 |
| 37208 | 7 |
| 38750 | 2 |
| 58218 | 2 |
| 36366 | 2 |
| 39950 | 2 |
| 35072 | 2 |
| 51106 | 2 |
| 42258 | 2 |
| 33382 | 2 |
| 36572 | 2 |
| 38630 | 2 |
| 38474 | 2 |
| 60332 | 2 |
| 41128 | 2 |
| 55764 | 2 |

## Attack Patterns
**Likely brute-force sources** (>= 5 auth attempts): 20

| IP | Auth Attempts |
|---|---:|
| `196.20.216.206` | 5778 |
| `106.38.51.68` | 1286 |
| `77.239.124.36` | 513 |
| `135.148.217.213` | 499 |
| `43.128.101.247` | 381 |
| `47.113.193.48` | 266 |
| `83.168.110.251` | 253 |
| `47.251.165.65` | 151 |
| `91.218.108.6` | 104 |
| `109.160.32.123` | 64 |
| `77.91.71.90` | 57 |
| `103.72.57.129` | 45 |
| `8.217.68.84` | 32 |
| `113.98.254.50` | 31 |
| `49.12.249.111` | 31 |
| `213.215.209.101` | 31 |
| `223.243.179.70` | 31 |
| `121.227.31.82` | 31 |
| `4.4.66.84` | 31 |
| `60.165.119.59` | 31 |

**Likely port-scan sources** (>= 5 distinct ports touched): 5

| IP | Distinct Ports |
|---|---:|
| `146.75.38.49` | 74 |
| `140.248.150.49` | 64 |
| `146.75.30.49` | 26 |
| `67.202.15.124` | 7 |
| `54.224.99.219` | 6 |

## Malware Families Detected
_Detected via Suricata alert signature matching - see docs/METHODOLOGY.md for caveats._

_None detected in this period._

## Top Credential Pairs Attempted
| Username | Password | Attempts |
|---|---|---:|
| `root` | `123456` | 25 |
| `root` | `admin` | 20 |
| `root` | `password` | 20 |
| `root` | `root` | 20 |
| `root` | `ubuntu` | 19 |
| `root` | `passwd` | 18 |
| `root` | `linux` | 18 |
| `root` | `qwerty` | 17 |
| `root` | `apache` | 17 |
| `root` | `guest` | 17 |
| `root` | `centos` | 16 |
| `root` | `nginx` | 16 |
| `root` | `mysql` | 16 |
| `root` | `docker` | 16 |
| `root` | `vps` | 16 |
| `root` | `host` | 16 |
| `root` | `www` | 16 |
| `root` | `web` | 16 |
| `root` | `default` | 16 |
| `root` | `administrator` | 16 |

## Timeline (daily)
| Date | Events |
|---|---:|
| 2026-10-05 | 1204 |
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
| 2026-11-01 | 2953 |
| 2026-11-02 | 2422 |
| 2026-11-03 | 11059 |
| 2026-11-04 | 7396 |

---
_Generated automatically by `scripts/analyze_logs.py`. See `scripts/generate_dashboard.py` for a chart-based HTML view of this same data._