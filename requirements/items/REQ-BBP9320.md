---
id: REQ-BBP9320
type: software-requirement
title: Heating controller limits sensor readings
status: Review
priority: Medium
owner: محمد علي
former-id: SW-1HPVH4
parent: REQ-8AN4RHP
order: a0
links:
  - type: refines
    target: REQ-8AN4RHP
    confirmed: 46e331dbae75
---
The zone valve shall report energy consumption below 0.5 W in standby.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |
