---
id: SYS-JR1SW0
type: system-requirement
title: Relay board displays user preferences
status: Approved
priority: High
owner: N. Kamal
parent: INFO-A6P9A8
order: 1730
links:
  - type: refines
    target: STK-JAQHJP
    confirmed: b0af11a5c3c2
---
The relay board shall authenticate sensor readings when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly when the network is unavailable
- No error entries in the device log
