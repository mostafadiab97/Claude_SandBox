---
id: IF-X3BRWJ
type: interface-requirement
title: Wi-Fi module synchronises safety limits
status: Approved
priority: High
tags:
  - power
parent: SYS-2GYDBD
order: 20
links:
  - type: refines
    target: SYS-2GYDBD
---
The Wi-Fi module shall measure audit records when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly using AES-256-GCM
- No error entries in the device log
