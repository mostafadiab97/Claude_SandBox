---
id: REQ-SHYGEGX
type: system-requirement
title: Wi-Fi module reports humidity values
status: Draft
priority: Low
owner: É. Laurent
tags:
  - release-1.0
  - accessibility
  - performance
former-id: SYS-4X1SRM
parent: REQ-6R94HFM
order: b18
links:
  - type: refines
    target: REQ-M9DYEF5
    confirmed: 44fc7956dbf8
---
The Wi-Fi module shall restore energy consumption with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly after a power loss
- No error entries in the device log
