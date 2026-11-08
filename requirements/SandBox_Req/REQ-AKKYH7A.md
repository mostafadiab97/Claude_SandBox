---
id: REQ-AKKYH7A
type: software-requirement
title: Telemetry pipeline calibrates the room temperature
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - connectivity
  - safety
former-id: SW-QYJRXE
parent: REQ-5JD6YSM
order: a2
links:
  - type: refines
    target: REQ-5JD6YSM
    confirmed: 0af8d7691be2
---
The telemetry pipeline shall validate safety limits using AES-256-GCM.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 23 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |
