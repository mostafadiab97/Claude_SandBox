---
id: REQ-0VFCCR7
type: system-requirement
title: Relay board encrypts user preferences
status: Draft
priority: Medium
owner: J. Müller
former-id: SYS-H7XP2M
parent: REQ-CMCS31A
order: b2D
links:
  - type: refines
    target: REQ-67MQ0AB
    confirmed: c77fe61daf4b
---
The relay board shall notify the connection state after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly using AES-256-GCM
- No error entries in the device log
