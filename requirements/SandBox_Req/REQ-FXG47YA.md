---
id: REQ-FXG47YA
type: hardware-requirement
title: Store the set point — detail
status: Approved
priority: Medium
owner: J. Müller
tags:
  - release-1.0
  - EMC
  - release-2.0
former-id: HW-383029
parent: REQ-07NE9TM
order: a0
links:
  - type: refines
    target: REQ-07NE9TM
    confirmed: bfa13e8c14f9
---
The telemetry pipeline shall store user preferences below 0.5 W in standby.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 20 | °C |
| Eco | 16 | °C |
| Frost protection | 7 | °C |
