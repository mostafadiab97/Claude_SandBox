---
id: SW-B5J7X8
type: software-requirement
title: User account service displays the set point
status: Review
priority: High
owner: Y. Saber
tags:
  - safety
  - regulatory
  - EMC
parent: SYS-ERJC40
order: 30
links:
  - type: refines
    target: SYS-ERJC40
    confirmed: f027b997b7f0
---
The telemetry pipeline shall store access tokens for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly using AES-256-GCM
- No error entries in the device log
