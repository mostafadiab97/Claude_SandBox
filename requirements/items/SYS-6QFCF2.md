---
id: SYS-6QFCF2
type: system-requirement
title: OTA server stores audit records
status: Draft
priority: High
owner: L. Samir
tags:
  - i18n
parent: INFO-YV5EZD
order: 540
links:
  - type: refines
    target: STK-JFBQPS
  - type: mitigates
    target: RSK-HKANA4
---
The OTA server shall authenticate relay events for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly for up to 8 zones
- No error entries in the device log
