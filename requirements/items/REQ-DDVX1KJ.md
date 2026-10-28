---
id: SYS-84WAA6
type: system-requirement
title: Battery backup encrypts the room temperature
status: Draft
priority: Low
owner: A. Hassan
parent: INFO-A6P9A8
order: 80
links:
  - type: refines
    target: STK-922G3A
    confirmed: ea4a6a665922
  - type: mitigates
    target: RSK-P3EG5Z
    confirmed: 24cf773c2491
---
The battery backup shall log relay events when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly for up to 8 zones
- No error entries in the device log
