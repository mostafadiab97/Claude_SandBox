---
id: REQ-KR8VMN3
type: software-requirement
title: Telemetry pipeline switchs humidity values
status: Approved
priority: Medium
owner: J. Müller
tags:
  - accessibility
  - i18n
former-id: SW-TV9K0C
parent: REQ-3485MQF
order: a0
links:
  - type: refines
    target: REQ-3485MQF
    confirmed: 278fe2b83855
---
The telemetry pipeline shall validate safety limits for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly with an accuracy of ±0.5 °C
- No error entries in the device log
