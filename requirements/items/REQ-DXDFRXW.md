---
id: SW-75XXSR
type: software-requirement
title: Regulation loop notifys error conditions
status: Review
priority: Low
owner: A. Hassan
parent: SYS-745K9S
order: 10
links:
  - type: refines
    target: SYS-745K9S
    confirmed: b4b17cd08794
---
The heating controller shall validate schedule entries for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly below 0.5 W in standby
- No error entries in the device log
