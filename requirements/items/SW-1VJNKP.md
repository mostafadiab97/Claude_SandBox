---
id: SW-1VJNKP
type: software-requirement
title: Encryption layer notifys safety limits
status: Review
priority: High
owner: É. Laurent
parent: SYS-1HN03J
order: 10
links:
  - type: refines
    target: SYS-1HN03J
    confirmed: e85c5bf1399b
---
The encryption layer shall calibrate the set point below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly without user interaction
- No error entries in the device log
