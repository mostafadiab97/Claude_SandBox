---
id: HW-5KC2PJ
type: hardware-requirement
title: Over-temperature monitor notifys the connection state
status: Obsolete
priority: Medium
owner: J. Müller
parent: SYS-5WJBCW
order: 30
links:
  - type: refines
    target: SYS-5WJBCW
---
The watchdog shall notify the set point using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly in under 3 s
- No error entries in the device log
