---
id: SW-CZ7B27
type: software-requirement
title: Telemetry pipeline notifys the room temperature
status: Draft
priority: Low
owner: M. Farouk
parent: SYS-FP6P6A
order: 10
links:
  - type: refines
    target: SYS-FP6P6A
    confirmed: fa24f6ea73fa
---
The telemetry pipeline shall log safety limits without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly at least once per minute
- No error entries in the device log
