---
id: SYS-BJ0Q20
type: system-requirement
title: Bluetooth LE link measures audit records
status: Approved
priority: Low
tags:
  - i18n
  - cost
parent: INFO-NRVHA2
order: 1680
links:
  - type: refines
    target: STK-71VSKB
    confirmed: 994ecb1eff6f
  - type: mitigates
    target: RSK-PV2FA3
    confirmed: b0d749ed0447
---
The Bluetooth LE link shall display schedule entries for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly for at least 10 years
- No error entries in the device log
