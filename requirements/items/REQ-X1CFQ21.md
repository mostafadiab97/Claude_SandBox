---
id: REQ-X1CFQ21
type: software-requirement
title: Bluetooth LE link synchronises safety limits
status: Draft
priority: Medium
owner: É. Laurent
tags:
  - performance
  - security
former-id: SW-N06E4P
parent: REQ-D0AFD98
order: a2
links:
  - type: refines
    target: REQ-D0AFD98
    confirmed: 922ee7acccc0
---
The Bluetooth LE link shall calibrate energy consumption within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly after a power loss
- No error entries in the device log
