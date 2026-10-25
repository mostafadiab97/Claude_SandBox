---
id: SYS-7WCAWK
type: system-requirement
title: Battery backup calibrates the operating mode
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - cost
  - i18n
parent: INFO-A6P9A8
order: 1200
links:
  - type: refines
    target: STK-CDR1Y9
    confirmed: d9857f8b33bf
  - type: mitigates
    target: RSK-W413B9
    confirmed: 1a4d2dc5e12b
---
The battery backup shall synchronise humidity values within 200 ms.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |
