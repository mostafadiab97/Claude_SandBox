---
id: REQ-DNKCN48
type: hardware-requirement
title: Heating controller authenticates energy consumption
status: Approved
priority: High
owner: H. Mostafa
tags:
  - security
  - release-1.0
  - cost
former-id: HW-7H6JEN
parent: REQ-E16RF9X
order: a0
links:
  - type: refines
    target: REQ-E16RF9X
    confirmed: cf6a8acfb8a2
---
The heating controller shall validate schedule entries with an accuracy of ±0.5 °C.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 23 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |
