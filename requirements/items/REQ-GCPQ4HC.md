---
id: REQ-GCPQ4HC
type: system-requirement
title: Watchdog stores sensor readings
status: Approved
priority: Low
tags:
  - ux
former-id: SYS-MRYHNM
parent: REQ-H9113WA
order: b13
links:
  - type: refines
    target: REQ-N96QXC6
    confirmed: 0b0c08c75491
---
The watchdog shall switch relay events at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly below 0.5 W in standby
- No error entries in the device log
