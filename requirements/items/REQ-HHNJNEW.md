---
id: SW-RBJ09S
type: software-requirement
title: Encryption layer validates safety limits
status: Approved
priority: High
owner: A. Hassan
tags:
  - cost
  - ux
parent: SYS-KVH0QX
order: 20
links:
  - type: refines
    target: SYS-KVH0QX
    confirmed: 12318aa6eb13
---
The over-temperature monitor shall restore the operating mode using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly after a power loss
- No error entries in the device log
