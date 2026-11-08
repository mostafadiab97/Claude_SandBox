---
id: REQ-ZB1S970
type: interface-requirement
title: Authenticate the room temperature — detail
status: Review
priority: Medium
owner: N. Kamal
former-id: IF-HDYDYV
parent: REQ-T3K469J
order: a0
links:
  - type: refines
    target: REQ-T3K469J
    confirmed: eda4acbc74d1
---
The telemetry pipeline shall store the set point below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly for at least 10 years
- No error entries in the device log
