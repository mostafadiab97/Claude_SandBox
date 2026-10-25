---
id: SW-YBBSY4
type: software-requirement
title: Regulation loop calibrates access tokens
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - performance
  - ux
parent: SYS-EC5N2Y
order: 20
links:
  - type: refines
    target: SYS-EC5N2Y
---
The regulation loop shall store the set point when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly below 0.5 W in standby
- No error entries in the device log
