---
id: REQ-RYXAYBT
type: software-requirement
title: User account service calibrates sensor readings
status: Draft
priority: Medium
tags:
  - performance
former-id: SW-V18C92
parent: REQ-D8575E7
order: a1
links:
  - type: refines
    target: REQ-D8575E7
    confirmed: 11ac230159e7
---
The telemetry pipeline shall notify humidity values within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly using AES-256-GCM
- No error entries in the device log
