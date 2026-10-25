---
id: IF-HY881D
type: interface-requirement
title: Mobile app validates sensor readings
status: Review
priority: High
owner: É. Laurent
tags:
  - security
  - release-1.0
parent: SYS-PERCNX
order: 10
links:
  - type: refines
    target: SYS-PERCNX
---
The login screen shall display the connection state in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly when the network is unavailable
- No error entries in the device log
