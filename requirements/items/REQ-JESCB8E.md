---
id: REQ-JESCB8E
type: software-requirement
title: Log humidity values — detail
status: Review
priority: Medium
owner: A. Hassan
former-id: SW-7416RW
parent: REQ-2RJWX8E
order: a0
links:
  - type: refines
    target: REQ-2RJWX8E
    confirmed: b52688ba9a63
---
The cloud backend shall validate schedule entries at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly at least once per minute
- No error entries in the device log
