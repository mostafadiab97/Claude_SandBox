---
id: REQ-4EGKDXG
type: interface-requirement
title: Switch relay events — detail
status: Review
priority: Medium
tags:
  - security
  - ux
former-id: IF-11QKAE
parent: REQ-NJHSY7A
order: a0
links:
  - type: refines
    target: REQ-NJHSY7A
    confirmed: cf712a2f2dbd
---
The heat pump driver shall synchronise access tokens below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly in under 3 s
- No error entries in the device log
