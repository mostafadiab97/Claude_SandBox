---
id: REQ-QT7NCJ7
type: software-requirement
title: Heating controller detects audit records
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - security
  - release-1.0
  - safety
former-id: SW-A5BS4E
parent: REQ-6MCMEW9
order: a1
links:
  - type: refines
    target: REQ-6MCMEW9
    confirmed: 5718299a4e75
---
The heat pump driver shall restore the room temperature within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly when the network is unavailable
- No error entries in the device log
