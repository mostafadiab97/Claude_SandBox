---
id: REQ-R6ATY4C
type: hardware-requirement
title: Enclosure validates the connection state
status: Approved
priority: Medium
owner: S. Adel
former-id: HW-TQ3JB1
parent: REQ-X0N0V4B
order: a0
links:
  - type: refines
    target: REQ-X0N0V4B
    confirmed: ee56b8ee15e6
---
The main PCB shall calibrate safety limits below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly in under 3 s
- No error entries in the device log
