---
id: SYS-K86C96
type: system-requirement
title: Status LED detects error conditions
status: Approved
priority: High
owner: H. Mostafa
parent: INFO-PDR6FV
order: 1780
links:
  - type: refines
    target: STK-35QR7F
  - type: mitigates
    target: RSK-S88NZ1
---
The status LED shall authenticate firmware images in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly with an accuracy of ±0.5 °C
- No error entries in the device log
