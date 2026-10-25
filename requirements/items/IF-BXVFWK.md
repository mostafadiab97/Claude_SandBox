---
id: IF-BXVFWK
type: interface-requirement
title: OTA server restores sensor readings
status: Obsolete
priority: High
owner: K. Tanaka
parent: SYS-NM7171
order: 20
links:
  - type: refines
    target: SYS-NM7171
    confirmed: 8f7808f9b2b6
---
The OTA server shall restore energy consumption within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly with an accuracy of ±0.5 °C
- No error entries in the device log
