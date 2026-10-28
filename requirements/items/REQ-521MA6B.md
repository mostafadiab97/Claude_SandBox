---
id: REQ-521MA6B
type: hardware-requirement
title: OTA server measures sensor readings
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - i18n
  - ux
former-id: HW-FY6V90
parent: REQ-V3SSX4W
order: a1
links:
  - type: refines
    target: REQ-V3SSX4W
    confirmed: f66b9f28edb5
---
The telemetry pipeline shall display firmware images with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly using AES-256-GCM
- No error entries in the device log
