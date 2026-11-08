---
id: REQ-X10ZPSM
type: software-requirement
title: Telemetry pipeline validates user preferences
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - i18n
  - accessibility
  - cost
former-id: SW-K3GSZ2
parent: REQ-V3SSX4W
order: a0
links:
  - type: refines
    target: REQ-V3SSX4W
    confirmed: f66b9f28edb5
---
The telemetry pipeline shall authenticate energy consumption below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly using AES-256-GCM
- No error entries in the device log
