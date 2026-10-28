---
id: REQ-9V4ZDEE
type: system-requirement
title: Menu system stores sensor readings
status: Approved
priority: Medium
owner: J. Müller
tags:
  - regulatory
  - connectivity
former-id: SYS-DVK0ST
parent: REQ-2ZA2TRZ
order: b2B
links:
  - type: refines
    target: REQ-VQBZQVC
    confirmed: 10d9c216aea2
---
The menu system shall calibrate sensor readings at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly in under 3 s
- No error entries in the device log
