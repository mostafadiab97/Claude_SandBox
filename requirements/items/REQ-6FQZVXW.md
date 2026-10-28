---
id: IF-XDZW70
type: interface-requirement
title: Relay board stores the set point
status: Review
priority: Low
owner: K. Tanaka
tags:
  - release-1.0
parent: SYS-CR4P8R
order: 10
links:
  - type: refines
    target: SYS-CR4P8R
    confirmed: 4c3ba50b83be
---
The battery backup shall restore relay events for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly after a power loss
- No error entries in the device log
