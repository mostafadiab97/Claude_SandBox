---
id: REQ-MN93TW7
type: software-requirement
title: Cloud backend detects the room temperature
status: Draft
priority: Low
tags:
  - EMC
  - i18n
  - performance
former-id: SW-H9TQJM
parent: REQ-P6D29TG
order: a0
links:
  - type: refines
    target: REQ-P6D29TG
    confirmed: 7e00d0c5709a
---
The OTA server shall detect schedule entries at least once per minute.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 21 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |
