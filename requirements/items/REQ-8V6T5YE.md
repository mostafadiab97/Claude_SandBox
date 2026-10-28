---
id: REQ-8V6T5YE
type: software-requirement
title: Detect the room temperature — detail
status: Approved
priority: Medium
owner: A. Hassan
former-id: SW-1RAJZZ
parent: REQ-BBVMMFN
order: a0
links:
  - type: refines
    target: REQ-BBVMMFN
    confirmed: 0c3dd50dc291
---
The telemetry pipeline shall restore relay events at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly after a power loss
- No error entries in the device log
