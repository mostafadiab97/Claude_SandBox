---
id: REQ-7N71AKR
type: system-requirement
title: Battery backup authenticates the room temperature
status: Approved
priority: Low
owner: K. Tanaka
former-id: SYS-M533EE
parent: REQ-CMCS31A
order: b1Q
links:
  - type: refines
    target: REQ-Z2PYD5A
    confirmed: 994b9d44bde8
---
The battery backup shall limit firmware images at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly when the network is unavailable
- No error entries in the device log
