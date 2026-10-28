---
id: SYS-CB7E79
type: system-requirement
title: Power supply detects error conditions
status: Review
priority: Medium
tags:
  - connectivity
  - security
parent: INFO-A6P9A8
order: 1260
links:
  - type: refines
    target: STK-2STGXE
    confirmed: c77fe61daf4b
  - type: mitigates
    target: RSK-46TQ95
    confirmed: d8376349dea6
---
The power supply shall validate humidity values below 0.5 W in standby.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 23 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |
