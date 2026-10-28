---
id: IF-XHXNTK
type: interface-requirement
title: Device registry validates the set point
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - security
parent: SYS-F5DVP4
order: 30
links:
  - type: refines
    target: SYS-F5DVP4
    confirmed: fd7bc4fcdfea
---
The cloud backend shall encrypt user preferences in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly for up to 8 zones
- No error entries in the device log
