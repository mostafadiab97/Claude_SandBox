---
id: REQ-Q3XX7E0
type: system-requirement
title: Encryption layer encrypts firmware images
status: Approved
priority: Medium
owner: K. Tanaka
former-id: SYS-N4MBK3
parent: REQ-H9113WA
order: aB
links:
  - type: refines
    target: REQ-375SK1B
    confirmed: ba30e28a130f
---
The encryption layer shall detect schedule entries when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly for up to 8 zones
- No error entries in the device log
