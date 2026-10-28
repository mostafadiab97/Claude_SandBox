---
id: REQ-JK7JQJK
type: interface-requirement
title: Tamper detection logs relay events
status: Approved
priority: Low
owner: É. Laurent
former-id: IF-QPDGVD
parent: REQ-M8Y2DK0
order: a1
links:
  - type: refines
    target: REQ-M8Y2DK0
    confirmed: 9d1ea6b10234
---
The tamper detection shall notify the operating mode below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly using AES-256-GCM
- No error entries in the device log
