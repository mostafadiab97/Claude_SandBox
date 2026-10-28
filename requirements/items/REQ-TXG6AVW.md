---
id: REQ-TXG6AVW
type: system-requirement
title: Encryption layer stores safety limits
status: Review
priority: High
owner: Y. Saber
tags:
  - regulatory
  - safety
  - EMC
former-id: SYS-RW42CM
parent: REQ-H9113WA
order: a0
links:
  - type: refines
    target: REQ-Z7761RK
    confirmed: 260bd01800c6
---
The encryption layer shall detect relay events below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly for at least 10 years
- No error entries in the device log
