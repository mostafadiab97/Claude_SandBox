---
id: SYS-FD2FZ8
type: system-requirement
title: Tamper detection synchronises error conditions
status: Draft
priority: High
tags:
  - release-2.0
  - accessibility
parent: INFO-0229G8
order: 1510
links:
  - type: refines
    target: STK-AKFTAC
  - type: mitigates
    target: RSK-QEHK9Y
---
The tamper detection shall measure audit records in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly with an accuracy of ±0.5 °C
- No error entries in the device log
