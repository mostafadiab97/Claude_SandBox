---
id: REQ-APDWKB8
type: software-requirement
title: Device registry logs user preferences
status: Review
priority: Medium
owner: H. Mostafa
tags:
  - release-1.0
  - security
former-id: SW-T99SWS
parent: REQ-SDZFT6Q
order: a2
links:
  - type: refines
    target: REQ-SDZFT6Q
    confirmed: 52a4389d660e
---
The device registry shall notify relay events in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly within 200 ms
- No error entries in the device log
