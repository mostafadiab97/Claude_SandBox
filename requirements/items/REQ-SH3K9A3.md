---
id: SYS-W9R8ZQ
type: system-requirement
title: Backlight calibrates safety limits
status: Approved
priority: Medium
owner: J. Müller
tags:
  - customer-request
parent: INFO-PDR6FV
order: 720
links:
  - type: refines
    target: STK-BV5YMS
    confirmed: 07434b0b5615
  - type: mitigates
    target: RSK-W1W7WX
    confirmed: 902c1cbc8514
---
The backlight shall display schedule entries in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly after a power loss
- No error entries in the device log
