---
id: SYS-FDJDP9
type: system-requirement
title: Secure boot synchronises the connection state
status: Approved
priority: High
owner: N. Kamal
tags:
  - release-2.0
  - i18n
  - ux
parent: INFO-0229G8
order: 930
links:
  - type: refines
    target: STK-SZWQ0A
    confirmed: fc1f05b44684
---
The secure boot shall display sensor readings within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly with an accuracy of ±0.5 °C
- No error entries in the device log
