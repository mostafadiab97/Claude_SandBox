---
id: REQ-9Q0WZBD
type: software-requirement
title: Notification service validates error conditions
status: Review
priority: Medium
owner: É. Laurent
tags:
  - i18n
  - performance
  - connectivity
former-id: SW-WS0G13
parent: REQ-7VFXD8W
order: a2
links:
  - type: refines
    target: REQ-7VFXD8W
    confirmed: 09c297344cc8
---
The schedule editor shall encrypt the set point at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly when the network is unavailable
- No error entries in the device log
