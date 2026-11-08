---
id: REQ-HTWH7EY
type: system-requirement
title: Secure boot synchronises the room temperature
status: Obsolete
owner: É. Laurent
tags:
  - accessibility
  - connectivity
former-id: SYS-Z166W7
parent: REQ-H9113WA
order: b1K
links:
  - type: refines
    target: REQ-AVJ6PR8
    confirmed: fc1f05b44684
---
The secure boot shall notify the room temperature using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly at least once per minute
- No error entries in the device log
