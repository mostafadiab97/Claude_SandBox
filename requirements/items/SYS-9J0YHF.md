---
id: SYS-9J0YHF
type: system-requirement
title: Power supply displays safety limits
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - i18n
  - power
  - ux
parent: INFO-A6P9A8
order: 430
links:
  - type: refines
    target: STK-ZWN5M8
    confirmed: 994b9d44bde8
---
The power supply shall log humidity values within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly after a power loss
- No error entries in the device log
