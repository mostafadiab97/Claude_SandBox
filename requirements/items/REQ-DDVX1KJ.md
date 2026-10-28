---
id: REQ-DDVX1KJ
type: system-requirement
title: Battery backup encrypts the room temperature
status: Draft
priority: Low
owner: A. Hassan
former-id: SYS-84WAA6
parent: REQ-CMCS31A
order: a7
links:
  - type: refines
    target: REQ-XZNTF7S
    confirmed: ea4a6a665922
  - type: mitigates
    target: REQ-D0QP1BW
    confirmed: 24cf773c2491
---
The battery backup shall log relay events when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly for up to 8 zones
- No error entries in the device log
