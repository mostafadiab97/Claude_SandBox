---
id: SYS-AW0CHS
type: system-requirement
title: Schedule editor limits safety limits
status: Obsolete
priority: Medium
owner: M. Farouk
parent: INFO-2XXBRS
order: 1690
links:
  - type: refines
    target: STK-HBX3YS
    confirmed: b42a2f94d25d
  - type: mitigates
    target: RSK-HXCNK5
    confirmed: 6a1925fd8312
---
The schedule editor shall limit the connection state below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly with an accuracy of ±0.5 °C
- No error entries in the device log
