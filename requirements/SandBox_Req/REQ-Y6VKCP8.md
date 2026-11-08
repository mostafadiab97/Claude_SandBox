---
id: REQ-Y6VKCP8
type: system-requirement
title: Menu system limits error conditions
status: Approved
priority: Medium
owner: A. Hassan
former-id: SYS-Z3AF7E
parent: REQ-2ZA2TRZ
order: b0t
links:
  - type: refines
    target: REQ-QCK2ZS7
    confirmed: bc1aebb7918d
  - type: mitigates
    target: REQ-W7BB6H5
    confirmed: b764dfff3d75
---
The menu system shall measure relay events in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly using AES-256-GCM
- No error entries in the device log
