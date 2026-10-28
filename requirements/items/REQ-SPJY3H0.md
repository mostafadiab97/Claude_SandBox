---
id: SW-SYVSE6
type: software-requirement
title: Over-temperature monitor detects access tokens
status: Review
priority: High
owner: K. Tanaka
tags:
  - security
  - EMC
  - accessibility
parent: SYS-4AZ7BD
order: 20
links:
  - type: refines
    target: SYS-4AZ7BD
    confirmed: cd9c225e18ad
---
The tamper detection shall notify the room temperature below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly in under 3 s
- No error entries in the device log
