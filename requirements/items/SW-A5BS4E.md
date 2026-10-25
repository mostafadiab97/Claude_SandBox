---
id: SW-A5BS4E
type: software-requirement
title: Heating controller detects audit records
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - security
  - release-1.0
  - safety
parent: SYS-HPD0VD
order: 20
links:
  - type: refines
    target: SYS-HPD0VD
---
The heat pump driver shall restore the room temperature within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly when the network is unavailable
- No error entries in the device log
