---
id: IF-9PH0KJ
type: interface-requirement
title: Schedule editor encrypts humidity values
status: Draft
priority: High
owner: J. Müller
tags:
  - security
  - connectivity
  - customer-request
parent: SYS-CHKY3X
order: 10
links:
  - type: refines
    target: SYS-CHKY3X
    confirmed: 3654ea6dcd35
---
The mobile app shall detect the set point below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly within 200 ms
- No error entries in the device log
