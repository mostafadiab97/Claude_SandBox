---
id: REQ-7G0D2YD
type: software-requirement
title: OTA server displays relay events
status: Draft
priority: Medium
owner: S. Adel
former-id: SW-N07K6R
parent: REQ-EP8W3RT
order: a0
links:
  - type: refines
    target: REQ-EP8W3RT
    confirmed: 1f0c64db8df4
---
The telemetry pipeline shall display the connection state at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly when the network is unavailable
- No error entries in the device log
