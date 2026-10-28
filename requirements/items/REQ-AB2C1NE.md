---
id: REQ-AB2C1NE
type: software-requirement
title: OTA server logs energy consumption
status: Obsolete
priority: Medium
owner: Y. Saber
tags:
  - release-1.0
former-id: SW-QKWM92
parent: REQ-K9CPZEQ
order: a2
links:
  - type: refines
    target: REQ-K9CPZEQ
    confirmed: 1d9be0f6bc96
---
The cloud backend shall switch the operating mode below 0.5 W in standby.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 23 | °C |
| Eco | 16 | °C |
| Frost protection | 7 | °C |
