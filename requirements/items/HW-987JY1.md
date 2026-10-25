---
id: HW-987JY1
type: hardware-requirement
title: Watchdog switchs sensor readings
status: Draft
priority: Low
owner: محمد علي
tags:
  - EMC
parent: SYS-2C5AG5
order: 20
links:
  - type: refines
    target: SYS-2C5AG5
    confirmed: f015c93439ed
---
The secure boot shall report the room temperature in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly with an accuracy of ±0.5 °C
- No error entries in the device log
