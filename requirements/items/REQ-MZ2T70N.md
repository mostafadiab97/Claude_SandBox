---
id: REQ-MZ2T70N
type: hardware-requirement
title: Pairing process detects sensor readings
status: Draft
priority: Medium
owner: N. Kamal
former-id: HW-6Z1BVX
parent: REQ-CJT5KJQ
order: a2
links:
  - type: refines
    target: REQ-CJT5KJQ
    confirmed: 05d37b4e999b
---
The pairing process shall report error conditions below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly in under 3 s
- No error entries in the device log
