---
title: HTB - Boardlight
date: 2025-01-01 17:30:00 +/-0900
categories: [Hack The Box, Linux]
tags: [htb-boardlight, hackthebox, nmap, wfuzz, dolibarr, cve-2023-30253, ssh, mysql, linpeas, cve-2022-37706]     # TAG names should always be lowercase
description: Hello
---

## Boardlight

![BoardLight](/assets/img/posts/htb-boardlight/BoardLight.png){: .center }
_BoardLight Machine info card_

### Machine info table

| Difficulty          | Easy     |
| OS               | Linux    |
| Released Date | 26 May 2024 |
| Machine State | Retired |

### Synopsis
Blah

## nmap
As always, starting with `nmap` port scan.

### TCP scan
```
tcp_ports=$(nmap -p- --min-rate 10000 $IP | grep '^[0-9]' |  cut -d '/' -f1 | tr '\n' ',' | sed s/,$//) && echo $tcp_ports
```

![nmap](/assets/img/posts/htb-boardlight/boardlight-1.png){: .center }