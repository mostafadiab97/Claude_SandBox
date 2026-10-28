---
id: SYS-E79TSB
type: system-requirement
title: Relay board authenticates error conditions
status: Review
priority: Medium
owner: Y. Saber
parent: INFO-A6P9A8
order: 1340
links:
  - type: refines
    target: STK-7F9256
    confirmed: 5588db2eb80a
  - type: mitigates
    target: RSK-4NE1NJ
    confirmed: 56f6781ca0d3
---
The relay board shall notify error conditions below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly below 0.5 W in standby
- No error entries in the device log
