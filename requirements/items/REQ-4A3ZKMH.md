---
id: REQ-4A3ZKMH
type: interface-requirement
title: Mobile app validates sensor readings
status: Review
priority: High
owner: É. Laurent
tags:
  - security
  - release-1.0
former-id: IF-HY881D
parent: REQ-1CGSZAR
order: a0
links:
  - type: refines
    target: REQ-1CGSZAR
    confirmed: 6bc9ba229103
---
The login screen shall display the connection state in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly when the network is unavailable
- No error entries in the device log
