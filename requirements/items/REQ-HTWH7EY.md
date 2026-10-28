---
id: SYS-Z166W7
type: system-requirement
title: Secure boot synchronises the room temperature
status: Obsolete
owner: É. Laurent
tags:
  - accessibility
  - connectivity
parent: INFO-0229G8
order: 1450
links:
  - type: refines
    target: STK-SZWQ0A
    confirmed: fc1f05b44684
---
The secure boot shall notify the room temperature using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly at least once per minute
- No error entries in the device log
