---
id: REQ-18EFAG8
type: system-requirement
title: Zone valve calibrates sensor readings
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - ux
former-id: SYS-6VZFH1
parent: REQ-7ED7ZET
order: b2R
links:
  - type: refines
    target: REQ-GHEE73G
    confirmed: 00c32cea6ea5
  - type: mitigates
    target: REQ-CYZ942A
    confirmed: 50cb7d905eb0
---
The zone valve shall restore humidity values in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly using AES-256-GCM
- No error entries in the device log
