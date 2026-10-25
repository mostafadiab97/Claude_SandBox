---
id: IF-5JGFQX
type: interface-requirement
title: Authenticate relay events — detail
status: Approved
priority: Medium
owner: L. Samir
tags:
  - cost
  - safety
  - customer-request
parent: IF-M7HYKX
order: 10
links:
  - type: refines
    target: IF-M7HYKX
    confirmed: 7174db36477e
---
The secure boot shall authenticate the room temperature when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly below 0.5 W in standby
- No error entries in the device log
