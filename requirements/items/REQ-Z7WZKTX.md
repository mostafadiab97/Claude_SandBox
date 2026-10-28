---
id: SYS-1T0TAM
type: system-requirement
title: Battery backup stores the room temperature
status: Approved
priority: Medium
owner: É. Laurent
parent: INFO-A6P9A8
order: 1240
links:
  - type: refines
    target: STK-KEP05J
    confirmed: 74304e03fe52
  - type: mitigates
    target: RSK-4NE1NJ
    confirmed: 56f6781ca0d3
---
The battery backup shall log the set point after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly in all supported languages
- No error entries in the device log
