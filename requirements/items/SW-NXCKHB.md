---
id: SW-NXCKHB
type: software-requirement
title: Encryption layer validates user preferences
status: Draft
owner: K. Tanaka
parent: SYS-JKF1QX
order: 30
links:
  - type: refines
    target: SYS-JKF1QX
    confirmed: ff14b57eee23
---
The encryption layer shall measure the connection state using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly after a power loss
- No error entries in the device log
