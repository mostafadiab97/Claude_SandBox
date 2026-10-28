---
id: SW-N06E4P
type: software-requirement
title: Bluetooth LE link synchronises safety limits
status: Draft
priority: Medium
owner: É. Laurent
tags:
  - performance
  - security
parent: SYS-PX6WZT
order: 30
links:
  - type: refines
    target: SYS-PX6WZT
    confirmed: 922ee7acccc0
---
The Bluetooth LE link shall calibrate energy consumption within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly after a power loss
- No error entries in the device log
