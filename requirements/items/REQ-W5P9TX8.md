---
id: REQ-W5P9TX8
type: hardware-requirement
title: Battery backup limits firmware images
status: Draft
priority: High
former-id: HW-381RQ1
parent: REQ-E8KNX06
order: a1
links:
  - type: refines
    target: REQ-E8KNX06
    confirmed: 7b1130aac0e9
---
The power supply shall notify the set point below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly in under 3 s
- No error entries in the device log
