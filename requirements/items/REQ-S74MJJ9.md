---
id: REQ-S74MJJ9
type: interface-requirement
title: Device registry restores safety limits
status: Draft
priority: Low
owner: M. Farouk
tags:
  - ux
  - power
  - cost
former-id: IF-MT3X0V
parent: REQ-7JRJWMP
order: a2
links:
  - type: refines
    target: REQ-7JRJWMP
    confirmed: d331f9bc5a8a
---
The OTA server shall store energy consumption without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly in under 3 s
- No error entries in the device log
