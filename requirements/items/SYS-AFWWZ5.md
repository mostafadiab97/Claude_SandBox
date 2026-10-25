---
id: SYS-AFWWZ5
type: system-requirement
title: Local API limits the set point
status: Draft
parent: INFO-NRVHA2
order: 1520
links:
  - type: refines
    target: STK-0AD5XP
    confirmed: 30e7f07df0d1
  - type: mitigates
    target: RSK-QP0EFZ
    confirmed: b4372c636b9e
---
The local API shall encrypt safety limits using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly using AES-256-GCM
- No error entries in the device log
