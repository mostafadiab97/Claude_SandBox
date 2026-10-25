---
id: SW-QC18BS
type: software-requirement
title: Local API switchs the operating mode
status: Review
priority: High
owner: J. Müller
tags:
  - ux
  - performance
  - release-1.0
parent: SYS-PX6WZT
order: 40
links:
  - type: refines
    target: SYS-PX6WZT
---
The Bluetooth LE link shall limit error conditions below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly for up to 8 zones
- No error entries in the device log
