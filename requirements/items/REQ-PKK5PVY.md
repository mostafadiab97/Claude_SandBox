---
id: REQ-PKK5PVY
type: software-requirement
title: Device registry calibrates the connection state
status: Draft
priority: High
owner: S. Adel
tags:
  - release-2.0
former-id: SW-G1NVQV
parent: REQ-21V318B
order: a0
links:
  - type: refines
    target: REQ-21V318B
    confirmed: e9e572deb541
---
The device registry shall limit user preferences with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly for up to 8 zones
- No error entries in the device log
