---
id: REQ-DXDFRXW
type: software-requirement
title: Regulation loop notifys error conditions
status: Review
priority: Low
owner: A. Hassan
former-id: SW-75XXSR
parent: REQ-16HDKES
order: a0
links:
  - type: refines
    target: REQ-16HDKES
    confirmed: b4b17cd08794
---
The heating controller shall validate schedule entries for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly below 0.5 W in standby
- No error entries in the device log
