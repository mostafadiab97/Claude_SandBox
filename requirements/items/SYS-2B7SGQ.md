---
id: SYS-2B7SGQ
type: system-requirement
title: OTA server calibrates the set point
status: Review
priority: Low
owner: A. Hassan
tags:
  - i18n
parent: INFO-YV5EZD
order: 220
links:
  - type: refines
    target: STK-SKPX7F
---
The OTA server shall report relay events within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly in under 3 s
- No error entries in the device log
