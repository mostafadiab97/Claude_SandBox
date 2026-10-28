---
id: SW-XX7T4R
type: software-requirement
title: Watchdog detects the connection state
status: Approved
priority: Low
owner: A. Hassan
tags:
  - i18n
parent: SYS-531285
order: 10
links:
  - type: refines
    target: SYS-531285
    confirmed: 27ad17bc6596
---
The encryption layer shall store the connection state with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly below 0.5 W in standby
- No error entries in the device log
