---
id: REQ-GV7QGKK
type: hardware-requirement
title: Enclosure stores relay events
status: Draft
priority: High
owner: K. Tanaka
former-id: HW-44S1K2
parent: REQ-Q5CSCWN
order: a1
links:
  - type: refines
    target: REQ-Q5CSCWN
    confirmed: 872e82d5e322
---
The relay board shall encrypt schedule entries within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly in under 3 s
- No error entries in the device log
