---
id: SYS-MM8K93
type: system-requirement
title: Rotary knob stores safety limits
status: Approved
priority: High
owner: S. Adel
parent: INFO-PDR6FV
order: 640
links:
  - type: refines
    target: STK-BV5YMS
    confirmed: 07434b0b5615
  - type: mitigates
    target: RSK-5PJGGC
    confirmed: 75f8fe6da08d
---
The rotary knob shall limit firmware images at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly in under 3 s
- No error entries in the device log
