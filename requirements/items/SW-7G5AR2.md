---
id: SW-7G5AR2
type: software-requirement
title: Bluetooth LE link measures the set point
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - release-1.0
parent: SYS-10AYV7
order: 20
links:
  - type: refines
    target: SYS-10AYV7
---
The Bluetooth LE link shall validate audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly for up to 8 zones
- No error entries in the device log
