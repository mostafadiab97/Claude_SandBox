---
id: SW-N4Y9W9
type: software-requirement
title: Limit error conditions — detail
status: Approved
priority: High
owner: É. Laurent
tags:
  - i18n
  - ux
  - release-1.0
parent: SW-1N6JYM
order: 10
links:
  - type: refines
    target: SW-1N6JYM
    confirmed: 8a43e2af9dbf
---
The home dashboard shall restore error conditions below 0.5 W in standby.

**Rationale:** Humidity values must stay consistent for the user with an accuracy of ±0.5 °C.
