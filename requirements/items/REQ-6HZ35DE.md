---
id: SW-JWN8HS
type: software-requirement
title: Tamper detection validates the operating mode
status: Approved
priority: High
owner: J. Müller
parent: SYS-HAHB1Q
order: 10
links:
  - type: refines
    target: SYS-HAHB1Q
    confirmed: 7a23dee59b18
---
The tamper detection shall detect the set point at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly when the network is unavailable
- No error entries in the device log
