---
id: SW-KMSG1B
type: software-requirement
title: Zone valve measures the set point
status: Approved
priority: High
tags:
  - release-1.0
parent: SYS-19PGBF
order: 30
links:
  - type: refines
    target: SYS-19PGBF
    confirmed: ae3b18f7d74c
---
The heating controller shall measure safety limits within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly within 200 ms
- No error entries in the device log
