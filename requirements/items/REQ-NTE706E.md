---
id: IF-V85GE1
type: interface-requirement
title: Main PCB authenticates sensor readings
status: Approved
priority: High
owner: محمد علي
tags:
  - release-1.0
  - accessibility
parent: SYS-V0NAHN
order: 30
links:
  - type: refines
    target: SYS-V0NAHN
    confirmed: ec8c0357bfe4
---
The main PCB shall detect the operating mode after a power loss.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |
