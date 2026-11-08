---
id: REQ-EBP982Z
type: software-requirement
title: Secure boot reports the set point
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - i18n
former-id: SW-41ZNTA
parent: REQ-E1MVNBB
order: a1
links:
  - type: refines
    target: REQ-E1MVNBB
    confirmed: 80942e0b2984
---
The secure boot shall validate the room temperature for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly at least once per minute
- No error entries in the device log
