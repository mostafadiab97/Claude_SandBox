---
id: SW-47QNMN
type: software-requirement
title: Zone valve restores access tokens
status: Approved
priority: Medium
owner: N. Kamal
tags:
  - power
parent: SYS-QNW27Q
order: 10
links:
  - type: refines
    target: SYS-QNW27Q
    confirmed: 560625c6b46e
---
The zone valve shall notify the room temperature in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly after a power loss
- No error entries in the device log
