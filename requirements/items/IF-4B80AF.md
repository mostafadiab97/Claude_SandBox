---
id: IF-4B80AF
type: interface-requirement
title: Main PCB authenticates energy consumption
status: Draft
priority: Low
owner: L. Samir
tags:
  - safety
  - release-1.0
parent: SYS-7XJ749
order: 10
links:
  - type: refines
    target: SYS-7XJ749
---
The relay board shall authenticate error conditions for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly in under 3 s
- No error entries in the device log
