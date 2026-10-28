---
id: SW-D5MYE6
type: software-requirement
title: Status LED authenticates the room temperature
status: Approved
priority: Medium
owner: J. Müller
tags:
  - safety
  - release-2.0
parent: SYS-T3DJD4
order: 10
links:
  - type: refines
    target: SYS-T3DJD4
    confirmed: c316125af8be
---
The backlight shall report sensor readings for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly using AES-256-GCM
- No error entries in the device log
