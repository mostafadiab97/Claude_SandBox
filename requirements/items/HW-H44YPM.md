---
id: HW-H44YPM
type: hardware-requirement
title: Power supply calibrates the set point
status: Review
owner: K. Tanaka
tags:
  - release-1.0
parent: SYS-M533EE
order: 30
links:
  - type: refines
    target: SYS-M533EE
---
The battery backup shall authenticate energy consumption below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly in under 3 s
- No error entries in the device log
