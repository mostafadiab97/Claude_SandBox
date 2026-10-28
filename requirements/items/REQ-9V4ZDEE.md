---
id: SYS-DVK0ST
type: system-requirement
title: Menu system stores sensor readings
status: Approved
priority: Medium
owner: J. Müller
tags:
  - regulatory
  - connectivity
parent: INFO-PDR6FV
order: 1980
links:
  - type: refines
    target: STK-KPV71Q
    confirmed: 10d9c216aea2
---
The menu system shall calibrate sensor readings at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly in under 3 s
- No error entries in the device log
