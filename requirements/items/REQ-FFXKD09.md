---
id: REQ-FFXKD09
type: interface-requirement
title: Schedule editor encrypts humidity values
status: Draft
priority: High
owner: J. Müller
tags:
  - security
  - connectivity
  - customer-request
former-id: IF-9PH0KJ
parent: REQ-A3PZBKA
order: a0
links:
  - type: refines
    target: REQ-A3PZBKA
    confirmed: 3654ea6dcd35
---
The mobile app shall detect the set point below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly within 200 ms
- No error entries in the device log
