---
id: REQ-KVCTPZX
type: software-requirement
title: Tamper detection detects safety limits
status: Approved
priority: Low
owner: J. Müller
tags:
  - connectivity
  - security
former-id: SW-18NMC0
parent: REQ-JM876BB
order: a0
links:
  - type: refines
    target: REQ-JM876BB
    confirmed: f3e9ccc7a316
---
The tamper detection shall log schedule entries in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly after a power loss
- No error entries in the device log
