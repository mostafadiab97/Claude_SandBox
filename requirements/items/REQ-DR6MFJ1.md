---
id: REQ-DR6MFJ1
type: system-requirement
title: Watchdog notifys the operating mode
status: Draft
priority: Low
owner: محمد علي
former-id: SYS-S1NHF1
parent: REQ-H9113WA
order: b1i
links:
  - type: refines
    target: REQ-375SK1B
    confirmed: ba30e28a130f
  - type: mitigates
    target: REQ-VYYM5AA
    confirmed: 637ec5e39d53
---
The watchdog shall encrypt the set point for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly with an accuracy of ±0.5 °C
- No error entries in the device log
