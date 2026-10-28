---
id: SW-YDDDH2
type: software-requirement
title: User account service detects the set point
status: Approved
priority: High
owner: J. Müller
tags:
  - cost
  - connectivity
  - regulatory
parent: SYS-BMNNFF
order: 20
links:
  - type: refines
    target: SYS-BMNNFF
    confirmed: e59e68c0f6b6
---
The OTA server shall log relay events in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly when the network is unavailable
- No error entries in the device log
