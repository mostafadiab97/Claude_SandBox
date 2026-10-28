---
id: REQ-XTW7B1R
type: system-requirement
title: User account service detects relay events
status: Review
priority: Medium
former-id: SYS-S5AVVB
parent: REQ-RE9ZKHF
order: a3
links:
  - type: refines
    target: REQ-ATQSVGJ
    confirmed: 2609d2cce998
---
The user account service shall report relay events when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly at least once per minute
- No error entries in the device log
