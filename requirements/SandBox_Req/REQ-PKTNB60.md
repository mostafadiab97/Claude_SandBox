---
id: REQ-PKTNB60
type: system-requirement
title: Secure boot restores safety limits
status: Obsolete
priority: High
owner: L. Samir
tags:
  - customer-request
former-id: SYS-VR1QT6
parent: REQ-H9113WA
order: b0C
links:
  - type: refines
    target: REQ-375SK1B
    confirmed: ba30e28a130f
---
The secure boot shall restore the room temperature when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly at least once per minute
- No error entries in the device log
