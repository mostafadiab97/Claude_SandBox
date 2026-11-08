---
id: REQ-R3R7FXA
type: software-requirement
title: OTA server validates relay events
status: Approved
priority: Medium
owner: L. Samir
tags:
  - safety
  - connectivity
former-id: SW-FJNHTZ
parent: REQ-7MXJ7E0
order: a1
links:
  - type: refines
    target: REQ-7MXJ7E0
    confirmed: fd7bc4fcdfea
---
The cloud backend shall validate schedule entries at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly in under 3 s
- No error entries in the device log
