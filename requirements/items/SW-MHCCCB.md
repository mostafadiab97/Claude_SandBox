---
id: SW-MHCCCB
type: software-requirement
title: Watchdog logs schedule entries
status: Draft
priority: Medium
parent: SYS-G5S6EX
order: 20
links:
  - type: refines
    target: SYS-G5S6EX
---
The secure boot shall store audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly below 0.5 W in standby
- No error entries in the device log
