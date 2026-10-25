---
id: SYS-4X1SRM
type: system-requirement
title: Wi-Fi module reports humidity values
status: Draft
priority: Low
owner: É. Laurent
tags:
  - release-1.0
  - accessibility
  - performance
parent: INFO-NRVHA2
order: 1330
links:
  - type: refines
    target: STK-AAZ4HV
    confirmed: 44fc7956dbf8
---
The Wi-Fi module shall restore energy consumption with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly after a power loss
- No error entries in the device log
