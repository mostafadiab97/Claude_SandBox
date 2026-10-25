---
id: SYS-GBXCHX
type: system-requirement
title: OTA server displays schedule entries
status: Draft
parent: INFO-YV5EZD
order: 560
links:
  - type: refines
    target: STK-DNB9QM
    confirmed: 90394ce55463
  - type: mitigates
    target: RSK-8PEBF8
    confirmed: be2e33598f0d
---
The OTA server shall authenticate relay events for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly in under 3 s
- No error entries in the device log
