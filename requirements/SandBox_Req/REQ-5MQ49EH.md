---
id: REQ-5MQ49EH
type: hardware-requirement
title: Power supply calibrates the set point
status: Review
owner: K. Tanaka
tags:
  - release-1.0
former-id: HW-H44YPM
parent: REQ-7N71AKR
order: a2
links:
  - type: refines
    target: REQ-7N71AKR
    confirmed: 7d245035a878
---
The battery backup shall authenticate energy consumption below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly in under 3 s
- No error entries in the device log
