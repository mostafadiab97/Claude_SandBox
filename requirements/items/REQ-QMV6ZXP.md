---
id: REQ-QMV6ZXP
type: system-requirement
title: Battery backup calibrates the operating mode
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - cost
  - i18n
former-id: SYS-7WCAWK
parent: REQ-CMCS31A
order: b0v
links:
  - type: refines
    target: REQ-QC1Z78M
    confirmed: d9857f8b33bf
  - type: mitigates
    target: REQ-187H7N8
    confirmed: 1a4d2dc5e12b
---
The battery backup shall synchronise humidity values within 200 ms.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |
