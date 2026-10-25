---
id: SYS-N4MBK3
type: system-requirement
title: Encryption layer encrypts firmware images
status: Approved
priority: Medium
owner: K. Tanaka
parent: INFO-0229G8
order: 120
links:
  - type: refines
    target: STK-DJ9M3M
    confirmed: ba30e28a130f
---
The encryption layer shall detect schedule entries when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly for up to 8 zones
- No error entries in the device log
