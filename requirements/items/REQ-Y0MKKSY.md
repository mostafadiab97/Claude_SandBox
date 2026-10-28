---
id: REQ-Y0MKKSY
type: software-requirement
title: Cloud backend notifys the connection state
status: Approved
former-id: SW-HJS6GR
parent: REQ-00CXS7S
order: a1
links:
  - type: refines
    target: REQ-00CXS7S
    confirmed: bc350f64bb32
---
The cloud backend shall encrypt the set point in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly after a power loss
- No error entries in the device log
