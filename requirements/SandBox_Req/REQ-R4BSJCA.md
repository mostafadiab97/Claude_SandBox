---
id: REQ-R4BSJCA
type: system-requirement
title: Zone valve authenticates firmware images
status: Approved
priority: Medium
tags:
  - security
former-id: SYS-F1Q0NC
parent: REQ-7ED7ZET
order: b1w
links:
  - type: refines
    target: REQ-219619F
    confirmed: 000356d5d38b
  - type: mitigates
    target: REQ-8G7SNRG
    confirmed: 872827ad2760
---
The zone valve shall encrypt the room temperature at least once per minute.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 21 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |
