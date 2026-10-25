---
id: SW-CYE22A
type: software-requirement
title: Backlight measures the set point
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - release-1.0
  - release-2.0
parent: SYS-378XSW
order: 10
links:
  - type: refines
    target: SYS-378XSW
---
The status LED shall calibrate user preferences without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly below 0.5 W in standby
- No error entries in the device log
