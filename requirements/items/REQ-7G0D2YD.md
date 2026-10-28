---
id: SW-N07K6R
type: software-requirement
title: OTA server displays relay events
status: Draft
priority: Medium
owner: S. Adel
parent: SYS-X7Q0GZ
order: 10
links:
  - type: refines
    target: SYS-X7Q0GZ
    confirmed: 1f0c64db8df4
---
The telemetry pipeline shall display the connection state at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly when the network is unavailable
- No error entries in the device log
