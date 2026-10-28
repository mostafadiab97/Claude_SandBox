---
id: REQ-PKF3YBD
type: system-requirement
title: Main PCB calibrates access tokens
status: Draft
priority: Low
owner: M. Farouk
tags:
  - security
former-id: SYS-SJNR25
parent: REQ-CMCS31A
order: b1f
links:
  - type: refines
    target: REQ-4H1F9N3
    confirmed: 96640a7e340d
---
The main PCB shall store relay events after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly using AES-256-GCM
- No error entries in the device log
