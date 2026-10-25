---
id: SYS-4JFYE9
type: system-requirement
title: Pairing process reports the room temperature
status: Approved
priority: High
owner: É. Laurent
tags:
  - security
parent: INFO-NRVHA2
order: 1710
links:
  - type: refines
    target: STK-F7D2QS
  - type: mitigates
    target: RSK-BXA4VK
---
The pairing process shall calibrate energy consumption below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly without user interaction
- No error entries in the device log
