---
id: IF-QKJ5PP
type: interface-requirement
title: Login screen calibrates access tokens
status: Approved
priority: Low
owner: A. Hassan
tags:
  - EMC
  - customer-request
  - performance
parent: SYS-0MK9ZW
order: 30
links:
  - type: refines
    target: SYS-0MK9ZW
---
The home dashboard shall display user preferences at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly using AES-256-GCM
- No error entries in the device log
