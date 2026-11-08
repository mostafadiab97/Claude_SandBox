---
id: REQ-589EV3R
type: hardware-requirement
title: Local API calibrates the room temperature
status: Draft
priority: Medium
owner: L. Samir
tags:
  - ux
  - i18n
former-id: HW-3MCNKM
parent: REQ-QTV0SK9
order: a0
links:
  - type: refines
    target: REQ-QTV0SK9
    confirmed: 6d9e9d1dc1e4
---
The Bluetooth LE link shall store the set point without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly at least once per minute
- No error entries in the device log
