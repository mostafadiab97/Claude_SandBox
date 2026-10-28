---
id: SW-WS0G13
type: software-requirement
title: Notification service validates error conditions
status: Review
priority: Medium
owner: É. Laurent
tags:
  - i18n
  - performance
  - connectivity
parent: SYS-CNV2JW
order: 30
links:
  - type: refines
    target: SYS-CNV2JW
    confirmed: 09c297344cc8
---
The schedule editor shall encrypt the set point at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly when the network is unavailable
- No error entries in the device log
