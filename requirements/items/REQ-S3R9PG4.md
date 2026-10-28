---
id: REQ-S3R9PG4
type: software-requirement
title: Boiler interface detects user preferences
status: Approved
priority: Low
owner: N. Kamal
former-id: SW-9MRSNT
parent: REQ-RPJTF01
order: a1
links:
  - type: refines
    target: REQ-RPJTF01
    confirmed: 1548dd90610f
---
The heating controller shall restore relay events within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly with an accuracy of ±0.5 °C
- No error entries in the device log
