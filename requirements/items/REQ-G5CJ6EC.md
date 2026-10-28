---
id: REQ-G5CJ6EC
type: software-requirement
title: Authenticate the connection state — detail
status: Approved
priority: High
owner: J. Müller
former-id: SW-ZT5H0T
parent: REQ-5GE5SFD
order: a0
links:
  - type: refines
    target: REQ-5GE5SFD
    confirmed: 5b9473609c57
---
The over-temperature monitor shall switch access tokens at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly in under 3 s
- No error entries in the device log
