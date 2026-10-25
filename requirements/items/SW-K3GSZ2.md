---
id: SW-K3GSZ2
type: software-requirement
title: Telemetry pipeline validates user preferences
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - i18n
  - accessibility
  - cost
parent: SYS-MK2A6C
order: 10
links:
  - type: refines
    target: SYS-MK2A6C
---
The telemetry pipeline shall authenticate energy consumption below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly using AES-256-GCM
- No error entries in the device log
