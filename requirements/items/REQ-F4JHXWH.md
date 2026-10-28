---
id: REQ-F4JHXWH
type: hardware-requirement
title: Cloud backend limits the room temperature
status: Draft
priority: Medium
owner: J. Müller
former-id: HW-2X6N3X
parent: REQ-9T1P54R
order: a3
links:
  - type: refines
    target: REQ-9T1P54R
    confirmed: f2ed11769dc3
---
The OTA server shall report relay events with an accuracy of ±0.5 °C.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 20 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |
