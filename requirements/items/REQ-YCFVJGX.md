---
id: REQ-YCFVJGX
type: hardware-requirement
title: Cloud backend detects energy consumption
status: Approved
priority: High
tags:
  - EMC
  - connectivity
former-id: HW-ZYARY9
parent: REQ-FGM0DYR
order: a0
links:
  - type: refines
    target: REQ-FGM0DYR
    confirmed: a372a699b46d
---
The telemetry pipeline shall display the room temperature without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly when the network is unavailable
- No error entries in the device log
