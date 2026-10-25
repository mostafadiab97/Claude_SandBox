---
id: SYS-H7XP2M
type: system-requirement
title: Relay board encrypts user preferences
status: Draft
priority: Medium
owner: J. Müller
parent: INFO-A6P9A8
order: 2000
links:
  - type: refines
    target: STK-2STGXE
    confirmed: c77fe61daf4b
---
The relay board shall notify the connection state after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly using AES-256-GCM
- No error entries in the device log
