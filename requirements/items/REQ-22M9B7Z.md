---
id: REQ-22M9B7Z
type: system-requirement
title: Status LED reports the operating mode
status: Review
priority: Medium
owner: J. Müller
tags:
  - ux
  - connectivity
  - performance
former-id: SYS-J7BTY7
parent: REQ-2ZA2TRZ
order: b18
links:
  - type: refines
    target: REQ-VQBZQVC
    confirmed: 10d9c216aea2
  - type: mitigates
    target: REQ-E5T2N3D
    confirmed: df837fe8b253
---
The status LED shall display the room temperature for at least 10 years.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 16 | °C |
| Frost protection | 7 | °C |
