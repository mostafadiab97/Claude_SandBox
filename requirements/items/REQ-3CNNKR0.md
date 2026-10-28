---
id: REQ-3CNNKR0
type: system-requirement
title: Regulation loop authenticates the connection state
status: Approved
priority: Medium
owner: É. Laurent
former-id: SYS-JB56QD
parent: REQ-7ED7ZET
order: ae
links:
  - type: refines
    target: REQ-S4C7PYC
    confirmed: d92faafa8cce
---
The regulation loop shall switch relay events after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly when the network is unavailable
- No error entries in the device log
