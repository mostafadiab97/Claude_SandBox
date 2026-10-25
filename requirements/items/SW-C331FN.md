---
id: SW-C331FN
type: software-requirement
title: Telemetry pipeline limits sensor readings
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - EMC
  - security
parent: SYS-FP6P6A
order: 40
links:
  - type: refines
    target: SYS-FP6P6A
---
The telemetry pipeline shall detect the set point in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly without user interaction
- No error entries in the device log
