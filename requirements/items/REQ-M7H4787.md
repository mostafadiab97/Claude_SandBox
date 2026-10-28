---
id: IF-RTND5Y
type: interface-requirement
title: Watchdog calibrates humidity values
status: Review
priority: Medium
tags:
  - security
  - EMC
  - release-1.0
parent: SYS-X6MHYX
order: 10
links:
  - type: refines
    target: SYS-X6MHYX
    confirmed: b63cacdcb2d3
---
The watchdog shall detect firmware images without user interaction.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 20 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |
