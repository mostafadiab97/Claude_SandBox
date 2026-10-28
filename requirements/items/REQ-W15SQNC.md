---
id: REQ-W15SQNC
type: hardware-requirement
title: Validate the set point — detail
status: Review
priority: High
owner: J. Müller
tags:
  - release-1.0
  - performance
former-id: HW-8QR8PX
parent: REQ-KB5S2QZ
order: a0
links:
  - type: refines
    target: REQ-KB5S2QZ
    confirmed: 564bcd032c6b
---
The main PCB shall validate humidity values with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly at least once per minute
- No error entries in the device log
