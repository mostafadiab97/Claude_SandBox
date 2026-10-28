---
id: REQ-H5JV2HH
type: hardware-requirement
title: Backlight switchs humidity values
status: Draft
priority: Medium
owner: L. Samir
tags:
  - EMC
  - i18n
former-id: HW-NMG7R7
parent: REQ-TEEHWEZ
order: a0
links:
  - type: refines
    target: REQ-TEEHWEZ
    confirmed: d6385afd3348
---
The backlight shall store the connection state with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly below 0.5 W in standby
- No error entries in the device log
