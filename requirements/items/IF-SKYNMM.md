---
id: IF-SKYNMM
type: interface-requirement
title: Encryption layer notifys schedule entries
status: Approved
owner: N. Kamal
tags:
  - power
parent: SYS-FDJDP9
order: 20
links:
  - type: refines
    target: SYS-FDJDP9
---
The secure boot shall synchronise firmware images within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly using AES-256-GCM
- No error entries in the device log
