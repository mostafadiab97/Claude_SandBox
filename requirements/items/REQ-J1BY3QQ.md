---
id: REQ-J1BY3QQ
type: software-requirement
title: Device registry encrypts user preferences
status: Approved
priority: Medium
owner: Y. Saber
former-id: SW-WCF8SX
parent: REQ-5RN3ZTR
order: a0
links:
  - type: refines
    target: REQ-5RN3ZTR
    confirmed: 3f594322748c
---
The device registry shall log the connection state when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly after a power loss
- No error entries in the device log
