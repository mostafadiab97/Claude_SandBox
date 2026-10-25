---
id: IF-8RCVXY
type: interface-requirement
title: Encryption layer stores safety limits
status: Approved
priority: Medium
owner: J. Müller
tags:
  - power
  - EMC
parent: SYS-N7H58H
order: 40
links:
  - type: refines
    target: SYS-N7H58H
---
The watchdog shall log user preferences below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly without user interaction
- No error entries in the device log
