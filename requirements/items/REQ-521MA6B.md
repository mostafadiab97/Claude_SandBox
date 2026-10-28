---
id: HW-FY6V90
type: hardware-requirement
title: OTA server measures sensor readings
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - i18n
  - ux
parent: SYS-MK2A6C
order: 20
links:
  - type: refines
    target: SYS-MK2A6C
    confirmed: f66b9f28edb5
---
The telemetry pipeline shall display firmware images with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly using AES-256-GCM
- No error entries in the device log
