---
id: REQ-6DRS9H6
type: hardware-requirement
title: Over-temperature monitor notifys the connection state
status: Obsolete
priority: Medium
owner: J. Müller
former-id: HW-5KC2PJ
parent: REQ-GQZG5M8
order: a2
links:
  - type: refines
    target: REQ-GQZG5M8
    confirmed: cd6c90a42873
---
The watchdog shall notify the set point using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly in under 3 s
- No error entries in the device log
