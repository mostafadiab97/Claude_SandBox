---
id: SW-1RAJZZ
type: software-requirement
title: Detect the room temperature — detail
status: Approved
priority: Medium
owner: A. Hassan
parent: SW-T021M5
order: 10
links:
  - type: refines
    target: SW-T021M5
---
The telemetry pipeline shall restore relay events at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly after a power loss
- No error entries in the device log
