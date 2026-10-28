---
id: REQ-VR0XBC8
type: software-requirement
title: User account service displays the set point
status: Review
priority: High
owner: Y. Saber
tags:
  - safety
  - regulatory
  - EMC
former-id: SW-B5J7X8
parent: REQ-FGY59FP
order: a2
links:
  - type: refines
    target: REQ-FGY59FP
    confirmed: f027b997b7f0
---
The telemetry pipeline shall store access tokens for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly using AES-256-GCM
- No error entries in the device log
