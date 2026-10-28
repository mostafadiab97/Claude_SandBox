---
id: REQ-D9WZPSF
type: software-requirement
title: Telemetry pipeline limits sensor readings
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - EMC
  - security
former-id: SW-C331FN
parent: REQ-E5D2PRV
order: a3
links:
  - type: refines
    target: REQ-E5D2PRV
    confirmed: 499135c7c771
---
The telemetry pipeline shall detect the set point in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly without user interaction
- No error entries in the device log
