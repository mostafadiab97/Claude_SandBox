---
id: REQ-2G8BXK6
type: software-requirement
title: User account service measures sensor readings
status: Review
priority: High
owner: É. Laurent
former-id: SW-N4K6A8
parent: REQ-F9D5TH0
order: a3
links:
  - type: refines
    target: REQ-F9D5TH0
    confirmed: 86d80fd5cb72
---
The device registry shall authenticate firmware images below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly after a power loss
- No error entries in the device log
