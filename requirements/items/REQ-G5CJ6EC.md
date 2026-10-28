---
id: SW-ZT5H0T
type: software-requirement
title: Authenticate the connection state — detail
status: Approved
priority: High
owner: J. Müller
parent: SW-7D21QR
order: 10
links:
  - type: refines
    target: SW-7D21QR
    confirmed: 5b9473609c57
---
The over-temperature monitor shall switch access tokens at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly in under 3 s
- No error entries in the device log
