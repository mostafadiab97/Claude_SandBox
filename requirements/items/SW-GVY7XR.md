---
id: SW-GVY7XR
type: software-requirement
title: Telemetry pipeline restores the operating mode
status: Draft
priority: Medium
parent: SYS-MDEDXA
order: 10
links:
  - type: refines
    target: SYS-MDEDXA
    confirmed: 1956ae8aa0df
---
The telemetry pipeline shall synchronise audit records below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly in under 3 s
- No error entries in the device log
