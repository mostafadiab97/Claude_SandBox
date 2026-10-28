---
id: REQ-HCXBR7T
type: software-requirement
title: OTA server authenticates the room temperature
status: Draft
owner: K. Tanaka
tags:
  - ux
  - EMC
former-id: SW-D40GPN
parent: REQ-DQ0W5RA
order: a0
links:
  - type: refines
    target: REQ-DQ0W5RA
    confirmed: 27661a1b1fc7
---
The telemetry pipeline shall report the set point at least once per minute.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 20 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |
