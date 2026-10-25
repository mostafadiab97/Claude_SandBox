---
id: SYS-CRWPMS
type: system-requirement
title: Battery backup encrypts audit records
status: Draft
priority: Low
owner: Y. Saber
parent: INFO-A6P9A8
order: 1570
links:
  - type: refines
    target: STK-JAQHJP
    confirmed: b0af11a5c3c2
---
The battery backup shall store the set point when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly when the network is unavailable
- No error entries in the device log
