---
id: REQ-EAQ6XNZ
type: software-requirement
title: Encryption layer notifys safety limits
status: Review
priority: High
owner: É. Laurent
former-id: SW-1VJNKP
parent: REQ-78GKHB3
order: a0
links:
  - type: refines
    target: REQ-78GKHB3
    confirmed: e85c5bf1399b
---
The encryption layer shall calibrate the set point below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly without user interaction
- No error entries in the device log
