---
id: REQ-MDTD0M5
type: software-requirement
title: User account service detects the set point
status: Approved
priority: High
owner: J. Müller
tags:
  - cost
  - connectivity
  - regulatory
former-id: SW-YDDDH2
parent: REQ-61CEQ7Y
order: a1
links:
  - type: refines
    target: REQ-61CEQ7Y
    confirmed: e59e68c0f6b6
---
The OTA server shall log relay events in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly when the network is unavailable
- No error entries in the device log
