---
id: HW-HZCN9G
type: hardware-requirement
title: Encryption layer notifys the operating mode
status: Approved
priority: Low
owner: M. Farouk
tags:
  - performance
  - security
parent: SYS-RX90D9
order: 20
links:
  - type: refines
    target: SYS-RX90D9
    confirmed: b0d94cbcb216
---
The tamper detection shall synchronise firmware images at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly within 200 ms
- No error entries in the device log
