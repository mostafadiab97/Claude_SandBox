---
id: REQ-Y4V4M30
type: software-requirement
title: Zone valve restores access tokens
status: Approved
priority: Medium
owner: N. Kamal
tags:
  - power
former-id: SW-47QNMN
parent: REQ-NBF8HWW
order: a0
links:
  - type: refines
    target: REQ-NBF8HWW
    confirmed: 560625c6b46e
---
The zone valve shall notify the room temperature in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly after a power loss
- No error entries in the device log
