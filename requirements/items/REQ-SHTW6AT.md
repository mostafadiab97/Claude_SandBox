---
id: REQ-SHTW6AT
type: system-requirement
title: Power supply detects error conditions
status: Review
priority: Medium
tags:
  - connectivity
  - security
former-id: SYS-CB7E79
parent: REQ-CMCS31A
order: b11
links:
  - type: refines
    target: REQ-67MQ0AB
    confirmed: c77fe61daf4b
  - type: mitigates
    target: REQ-PWM7XS5
    confirmed: d8376349dea6
---
The power supply shall validate humidity values below 0.5 W in standby.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 23 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |
