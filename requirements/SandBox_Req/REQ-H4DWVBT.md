---
id: REQ-H4DWVBT
type: hardware-requirement
title: User account service detects sensor readings
status: Draft
priority: High
owner: Y. Saber
tags:
  - release-1.0
  - accessibility
former-id: HW-P9S47B
parent: REQ-9FZHANA
order: a2
links:
  - type: refines
    target: REQ-9FZHANA
    confirmed: 08cad2a24d2f
---
The OTA server shall limit the set point at least once per minute.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 20 | °C |
| Eco | 16 | °C |
| Frost protection | 7 | °C |
