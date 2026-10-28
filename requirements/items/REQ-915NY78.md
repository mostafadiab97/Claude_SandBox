---
id: IF-1E4QDT
type: interface-requirement
title: Backlight stores sensor readings
status: Approved
priority: High
owner: R. Nabil
tags:
  - performance
  - ux
parent: SYS-XPCTNY
order: 20
links:
  - type: refines
    target: SYS-XPCTNY
    confirmed: 042eed4f2a11
---
The backlight shall synchronise the connection state for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly below 0.5 W in standby
- No error entries in the device log
