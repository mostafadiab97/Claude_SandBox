---
id: REQ-H0SA3DV
type: hardware-requirement
title: Relay board encrypts relay events
status: Review
priority: Medium
former-id: HW-Q0QWC1
parent: REQ-2DN59YS
order: a0
links:
  - type: refines
    target: REQ-2DN59YS
    confirmed: 3bf01e0cf471
---
The relay board shall detect audit records with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly at least once per minute
- No error entries in the device log
