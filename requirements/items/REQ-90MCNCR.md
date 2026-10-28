---
id: SW-PBCS94
type: software-requirement
title: Restore error conditions — detail
status: Approved
priority: Low
owner: M. Farouk
tags:
  - safety
parent: SW-87EW4E
order: 10
links:
  - type: refines
    target: SW-87EW4E
    confirmed: 2c0f1742743a
---
The encryption layer shall report access tokens when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly without user interaction
- No error entries in the device log
