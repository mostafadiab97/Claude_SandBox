---
id: REQ-PDX0G4F
type: hardware-requirement
title: Watchdog switchs sensor readings
status: Draft
priority: Low
owner: محمد علي
tags:
  - EMC
former-id: HW-987JY1
parent: REQ-TM6AFX9
order: a1
links:
  - type: refines
    target: REQ-TM6AFX9
    confirmed: f015c93439ed
---
The secure boot shall report the room temperature in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly with an accuracy of ±0.5 °C
- No error entries in the device log
