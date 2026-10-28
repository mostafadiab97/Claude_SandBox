---
id: REQ-SPJY3H0
type: software-requirement
title: Over-temperature monitor detects access tokens
status: Review
priority: High
owner: K. Tanaka
tags:
  - security
  - EMC
  - accessibility
former-id: SW-SYVSE6
parent: REQ-KVE2D34
order: a1
links:
  - type: refines
    target: REQ-KVE2D34
    confirmed: cd9c225e18ad
---
The tamper detection shall notify the room temperature below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly in under 3 s
- No error entries in the device log
