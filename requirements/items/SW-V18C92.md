---
id: SW-V18C92
type: software-requirement
title: User account service calibrates sensor readings
status: Draft
priority: Medium
tags:
  - performance
parent: SYS-D4W333
order: 20
links:
  - type: refines
    target: SYS-D4W333
    confirmed: 11ac230159e7
---
The telemetry pipeline shall notify humidity values within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly using AES-256-GCM
- No error entries in the device log
