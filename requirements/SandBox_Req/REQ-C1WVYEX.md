---
id: REQ-C1WVYEX
type: software-requirement
title: Telemetry pipeline notifys the room temperature
status: Draft
priority: Low
owner: M. Farouk
former-id: SW-CZ7B27
parent: REQ-E5D2PRV
order: a0
links:
  - type: refines
    target: REQ-E5D2PRV
    confirmed: fa24f6ea73fa
---
The telemetry pipeline shall log safety limits without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly at least once per minute
- No error entries in the device log
