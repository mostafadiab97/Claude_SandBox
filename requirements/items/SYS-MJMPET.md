---
id: SYS-MJMPET
type: system-requirement
title: Login screen detects safety limits
status: Review
priority: Medium
tags:
  - safety
  - ux
  - connectivity
parent: INFO-2XXBRS
order: 580
links:
  - type: refines
    target: STK-B9Y7CM
    confirmed: 2e83dea5db22
---
The login screen shall detect relay events within 200 ms.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |
