---
id: REQ-6HYHTXA
type: software-requirement
title: Backlight calibrates firmware images
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - release-1.0
  - ux
former-id: SW-2QPRVH
parent: REQ-0WX3PV8
order: a1
links:
  - type: refines
    target: REQ-0WX3PV8
    confirmed: 4dad1a572bf6
---
The status LED shall switch schedule entries with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly within 200 ms
- No error entries in the device log
