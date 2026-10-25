---
id: SW-THVK2Q
type: software-requirement
title: OTA server detects safety limits
status: Approved
priority: High
owner: M. Farouk
tags:
  - performance
parent: SYS-XZE9DK
order: 30
links:
  - type: refines
    target: SYS-XZE9DK
---
The user account service shall switch relay events below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly without user interaction
- No error entries in the device log
