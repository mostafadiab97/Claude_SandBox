---
id: REQ-0PQQJHJ
type: interface-requirement
title: Over-temperature monitor reports the connection state
status: Draft
priority: Medium
owner: A. Hassan
former-id: IF-PRKC7B
parent: REQ-BZPV0PM
order: a0
links:
  - type: refines
    target: REQ-BZPV0PM
    confirmed: 7f8ed4700350
---
The secure boot shall display relay events at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly after a power loss
- No error entries in the device log
