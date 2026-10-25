---
id: IF-11QKAE
type: interface-requirement
title: Switch relay events — detail
status: Review
priority: Medium
tags:
  - security
  - ux
parent: IF-WT0723
order: 10
links:
  - type: refines
    target: IF-WT0723
---
The heat pump driver shall synchronise access tokens below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly in under 3 s
- No error entries in the device log
