---
id: IF-1CBAMV
type: interface-requirement
title: Schedule editor calibrates access tokens
status: Review
priority: Low
tags:
  - security
  - cost
parent: SYS-0N6C2D
order: 20
links:
  - type: refines
    target: SYS-0N6C2D
    confirmed: 50615d725109
---
The login screen shall encrypt access tokens when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly at least once per minute
- No error entries in the device log
