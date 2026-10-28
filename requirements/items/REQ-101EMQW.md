---
id: SYS-XDP32K
type: system-requirement
title: Relay board restores safety limits
status: Draft
priority: High
owner: R. Nabil
parent: INFO-A6P9A8
order: 2360
links:
  - type: refines
    target: STK-KEP05J
    confirmed: 74304e03fe52
  - type: mitigates
    target: RSK-P3EG5Z
    confirmed: 24cf773c2491
---
The relay board shall calibrate the set point in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly after a power loss
- No error entries in the device log
