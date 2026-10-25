---
id: SW-N6PBSA
type: software-requirement
title: Telemetry pipeline authenticates sensor readings
status: Draft
priority: High
owner: A. Hassan
tags:
  - security
  - cost
  - release-2.0
parent: SYS-PYKN9H
order: 10
links:
  - type: refines
    target: SYS-PYKN9H
    confirmed: 745545e6884a
---
The telemetry pipeline shall validate sensor readings for up to 8 zones.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 20 | °C |
| Eco | 16 | °C |
| Frost protection | 7 | °C |
