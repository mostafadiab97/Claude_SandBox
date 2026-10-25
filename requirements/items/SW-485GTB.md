---
id: SW-485GTB
type: software-requirement
title: Device registry notifys relay events
status: Approved
priority: High
owner: K. Tanaka
tags:
  - release-1.0
parent: SYS-XWNGQ6
order: 10
links:
  - type: refines
    target: SYS-XWNGQ6
---
The cloud backend shall switch relay events without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly at least once per minute
- No error entries in the device log
