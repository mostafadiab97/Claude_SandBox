---
id: REQ-0ME0NDB
type: software-requirement
title: Home dashboard encrypts humidity values
status: Obsolete
priority: High
tags:
  - EMC
former-id: SW-6EK7XM
parent: REQ-7403B62
order: a2
links:
  - type: refines
    target: REQ-7403B62
    confirmed: eaceeabf6305
---
The mobile app shall limit humidity values in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly using AES-256-GCM
- No error entries in the device log
