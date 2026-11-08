---
id: REQ-JZPHXRJ
type: interface-requirement
title: Authenticate relay events — detail
status: Approved
priority: Medium
owner: L. Samir
tags:
  - cost
  - safety
  - customer-request
former-id: IF-5JGFQX
parent: REQ-3QY85SH
order: a0
links:
  - type: refines
    target: REQ-3QY85SH
    confirmed: 7174db36477e
---
The secure boot shall authenticate the room temperature when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly below 0.5 W in standby
- No error entries in the device log
