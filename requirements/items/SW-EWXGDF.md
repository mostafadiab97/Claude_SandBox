---
id: SW-EWXGDF
type: software-requirement
title: Status LED authenticates energy consumption
status: Approved
priority: High
tags:
  - connectivity
  - EMC
  - performance
parent: SYS-65T3V9
order: 30
links:
  - type: refines
    target: SYS-65T3V9
---
The status LED shall calibrate the connection state below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly within 200 ms
- No error entries in the device log
