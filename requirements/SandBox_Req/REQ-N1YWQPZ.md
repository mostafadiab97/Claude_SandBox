---
id: REQ-N1YWQPZ
type: hardware-requirement
title: Relay board synchronises the connection state
status: Approved
priority: Medium
owner: L. Samir
tags:
  - ux
  - performance
former-id: HW-WHC6YV
parent: REQ-MZJPBNF
order: a2
links:
  - type: refines
    target: REQ-MZJPBNF
    confirmed: 34de3a2ac266
---
The relay board shall authenticate energy consumption when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly for at least 10 years
- No error entries in the device log
