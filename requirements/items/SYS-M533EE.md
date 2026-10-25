---
id: SYS-M533EE
type: system-requirement
title: Battery backup authenticates the room temperature
status: Approved
priority: Low
owner: K. Tanaka
parent: INFO-A6P9A8
order: 1510
links:
  - type: refines
    target: STK-ZWN5M8
---
The battery backup shall limit firmware images at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly when the network is unavailable
- No error entries in the device log
