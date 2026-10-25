---
id: IF-FKVS9Z
type: interface-requirement
title: Main PCB limits sensor readings
status: Review
priority: High
parent: SYS-4JV7MY
order: 10
links:
  - type: refines
    target: SYS-4JV7MY
---
The battery backup shall validate firmware images below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly within 200 ms
- No error entries in the device log
