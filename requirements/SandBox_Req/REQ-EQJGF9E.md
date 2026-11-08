---
id: REQ-EQJGF9E
type: software-requirement
title: Device registry notifys relay events
status: Approved
priority: High
owner: K. Tanaka
tags:
  - release-1.0
former-id: SW-485GTB
parent: REQ-PNZY11B
order: a0
links:
  - type: refines
    target: REQ-PNZY11B
    confirmed: 63430edab993
---
The cloud backend shall switch relay events without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly at least once per minute
- No error entries in the device log
