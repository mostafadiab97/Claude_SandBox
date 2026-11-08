---
id: REQ-BM7070Z
type: interface-requirement
title: Schedule editor calibrates access tokens
status: Review
priority: Low
tags:
  - security
  - cost
former-id: IF-1CBAMV
parent: REQ-G9QWE5X
order: a1
links:
  - type: refines
    target: REQ-G9QWE5X
    confirmed: 50615d725109
---
The login screen shall encrypt access tokens when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly at least once per minute
- No error entries in the device log
