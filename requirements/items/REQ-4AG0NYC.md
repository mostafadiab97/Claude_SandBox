---
id: REQ-4AG0NYC
type: interface-requirement
title: Main PCB limits sensor readings
status: Review
priority: High
former-id: IF-FKVS9Z
parent: REQ-EKP7AXG
order: a0
links:
  - type: refines
    target: REQ-EKP7AXG
    confirmed: 199fce62923b
---
The battery backup shall validate firmware images below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly within 200 ms
- No error entries in the device log
