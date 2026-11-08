---
id: REQ-C714MBD
type: interface-requirement
title: Login screen calibrates access tokens
status: Approved
priority: Low
owner: A. Hassan
tags:
  - EMC
  - customer-request
  - performance
former-id: IF-QKJ5PP
parent: REQ-YW090BX
order: a2
links:
  - type: refines
    target: REQ-YW090BX
    confirmed: 5727fec8b08d
---
The home dashboard shall display user preferences at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly using AES-256-GCM
- No error entries in the device log
