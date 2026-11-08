---
id: REQ-X2C1RSX
type: interface-requirement
title: Encryption layer stores safety limits
status: Approved
priority: Medium
owner: J. Müller
tags:
  - power
  - EMC
former-id: IF-8RCVXY
parent: REQ-9T92A3R
order: a3
links:
  - type: refines
    target: REQ-9T92A3R
    confirmed: a8a06726344d
---
The watchdog shall log user preferences below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly without user interaction
- No error entries in the device log
