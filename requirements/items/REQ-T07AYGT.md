---
id: REQ-T07AYGT
type: hardware-requirement
title: Heat pump driver authenticates error conditions
status: Approved
priority: High
owner: É. Laurent
tags:
  - accessibility
  - connectivity
former-id: HW-DZTYK4
parent: REQ-SCHE89Y
order: a0
links:
  - type: refines
    target: REQ-SCHE89Y
    confirmed: 7c5c5ce3bd83
---
The heat pump driver shall restore the set point using AES-256-GCM.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 23 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |
