---
id: SYS-RW42CM
type: system-requirement
title: Encryption layer stores safety limits
status: Review
priority: High
owner: Y. Saber
tags:
  - regulatory
  - safety
  - EMC
parent: INFO-0229G8
order: 10
links:
  - type: refines
    target: STK-92HHJV
    confirmed: 260bd01800c6
---
The encryption layer shall detect relay events below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly for at least 10 years
- No error entries in the device log
