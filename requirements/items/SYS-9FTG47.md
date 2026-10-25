---
id: SYS-9FTG47
type: system-requirement
title: Secure boot switchs the set point
status: Review
priority: Medium
owner: J. Müller
parent: INFO-0229G8
order: 490
links:
  - type: refines
    target: STK-ZJRWCQ
    confirmed: dc746945e71d
  - type: mitigates
    target: RSK-4SK8XQ
    confirmed: d8a03dc18226
---
The secure boot shall report sensor readings below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly for at least 10 years
- No error entries in the device log
