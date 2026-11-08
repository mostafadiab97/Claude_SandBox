---
id: REQ-VK0W78K
type: software-requirement
title: Encryption layer validates user preferences
status: Draft
owner: K. Tanaka
former-id: SW-NXCKHB
parent: REQ-4Q67RJE
order: a2
links:
  - type: refines
    target: REQ-4Q67RJE
    confirmed: ff14b57eee23
---
The encryption layer shall measure the connection state using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly after a power loss
- No error entries in the device log
