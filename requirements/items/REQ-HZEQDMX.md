---
id: REQ-HZEQDMX
type: system-requirement
title: Login screen detects safety limits
status: Review
priority: Medium
tags:
  - safety
  - ux
  - connectivity
former-id: SYS-MJMPET
parent: REQ-QYXGSQ4
order: av
links:
  - type: refines
    target: REQ-YGQ30E7
    confirmed: 2e83dea5db22
---
The login screen shall detect relay events within 200 ms.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |
