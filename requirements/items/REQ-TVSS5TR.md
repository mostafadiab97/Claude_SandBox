---
id: REQ-TVSS5TR
type: software-requirement
title: Status LED authenticates energy consumption
status: Approved
priority: High
tags:
  - connectivity
  - EMC
  - performance
former-id: SW-EWXGDF
parent: REQ-4YNA756
order: a2
links:
  - type: refines
    target: REQ-4YNA756
    confirmed: ccd727c8c684
---
The status LED shall calibrate the connection state below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly within 200 ms
- No error entries in the device log
