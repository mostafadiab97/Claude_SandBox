---
id: REQ-6HZ35DE
type: software-requirement
title: Tamper detection validates the operating mode
status: Approved
priority: High
owner: J. Müller
former-id: SW-JWN8HS
parent: REQ-ZTVJEZ4
order: a0
links:
  - type: refines
    target: REQ-ZTVJEZ4
    confirmed: 7a23dee59b18
---
The tamper detection shall detect the set point at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly when the network is unavailable
- No error entries in the device log
