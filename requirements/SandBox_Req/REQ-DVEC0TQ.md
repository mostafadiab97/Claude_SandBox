---
id: REQ-DVEC0TQ
type: interface-requirement
title: OTA server restores sensor readings
status: Obsolete
priority: High
owner: K. Tanaka
former-id: IF-BXVFWK
parent: REQ-ZF5TC5N
order: a1
links:
  - type: refines
    target: REQ-ZF5TC5N
    confirmed: 8f7808f9b2b6
---
The OTA server shall restore energy consumption within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly with an accuracy of ±0.5 °C
- No error entries in the device log
