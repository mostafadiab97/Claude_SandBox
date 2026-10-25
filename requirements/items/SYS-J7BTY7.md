---
id: SYS-J7BTY7
type: system-requirement
title: Status LED reports the operating mode
status: Review
priority: Medium
owner: J. Müller
tags:
  - ux
  - connectivity
  - performance
parent: INFO-PDR6FV
order: 1330
links:
  - type: refines
    target: STK-KPV71Q
    confirmed: 10d9c216aea2
  - type: mitigates
    target: RSK-81XFR0
    confirmed: df837fe8b253
---
The status LED shall display the room temperature for at least 10 years.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 16 | °C |
| Frost protection | 7 | °C |
