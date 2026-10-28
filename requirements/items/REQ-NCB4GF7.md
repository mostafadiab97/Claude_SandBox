---
id: REQ-NCB4GF7
type: interface-requirement
title: Encryption layer notifys schedule entries
status: Approved
owner: N. Kamal
tags:
  - power
former-id: IF-SKYNMM
parent: REQ-AR75A1G
order: a1
links:
  - type: refines
    target: REQ-AR75A1G
    confirmed: 3facea10cce7
---
The secure boot shall synchronise firmware images within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly using AES-256-GCM
- No error entries in the device log
