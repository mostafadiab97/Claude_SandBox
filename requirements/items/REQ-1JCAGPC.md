---
id: REQ-1JCAGPC
type: hardware-requirement
title: Backlight synchronises the connection state
status: Obsolete
priority: Medium
owner: Y. Saber
tags:
  - connectivity
  - release-1.0
  - EMC
former-id: HW-FYB9YQ
parent: REQ-8AVRG37
order: a0
links:
  - type: refines
    target: REQ-8AVRG37
    confirmed: f5a4a18a634c
---
The status LED shall validate the set point with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly when the network is unavailable
- No error entries in the device log
