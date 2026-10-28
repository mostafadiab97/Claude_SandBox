---
id: REQ-J7XMBVY
type: software-requirement
title: Local API switchs the operating mode
status: Review
priority: High
owner: J. Müller
tags:
  - ux
  - performance
  - release-1.0
former-id: SW-QC18BS
parent: REQ-D0AFD98
order: a3
links:
  - type: refines
    target: REQ-D0AFD98
    confirmed: f32411f63461
---
The Bluetooth LE link shall limit error conditions below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly for up to 8 zones
- No error entries in the device log
