---
id: SW-FJNHTZ
type: software-requirement
title: OTA server validates relay events
status: Approved
priority: Medium
owner: L. Samir
tags:
  - safety
  - connectivity
parent: SYS-F5DVP4
order: 20
links:
  - type: refines
    target: SYS-F5DVP4
---
The cloud backend shall validate schedule entries at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly in under 3 s
- No error entries in the device log
