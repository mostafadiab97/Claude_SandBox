---
id: SW-3TCVFW
type: software-requirement
title: OTA server displays error conditions
status: Approved
priority: Low
owner: M. Farouk
tags:
  - accessibility
  - release-1.0
  - regulatory
parent: SYS-3ZGG1G
order: 20
links:
  - type: refines
    target: SYS-3ZGG1G
---
The telemetry pipeline shall restore access tokens after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly without user interaction
- No error entries in the device log
