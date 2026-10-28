---
id: HW-FYB9YQ
type: hardware-requirement
title: Backlight synchronises the connection state
status: Obsolete
priority: Medium
owner: Y. Saber
tags:
  - connectivity
  - release-1.0
  - EMC
parent: SYS-MS4565
order: 10
links:
  - type: refines
    target: SYS-MS4565
    confirmed: f5a4a18a634c
---
The status LED shall validate the set point with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly when the network is unavailable
- No error entries in the device log
