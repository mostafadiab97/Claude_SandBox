---
id: REQ-3WYV9EB
type: interface-requirement
title: Backlight authenticates the room temperature
status: Review
priority: High
owner: Y. Saber
tags:
  - security
  - regulatory
  - accessibility
former-id: IF-M12QVM
parent: REQ-X57Z6YA
order: a2
links:
  - type: refines
    target: REQ-X57Z6YA
    confirmed: 06d6346c072b
---
The menu system shall authenticate relay events using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly within 200 ms
- No error entries in the device log
