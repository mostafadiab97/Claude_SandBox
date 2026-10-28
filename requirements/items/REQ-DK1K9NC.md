---
id: REQ-DK1K9NC
type: system-requirement
title: Secure boot authenticates firmware images
status: Approved
priority: High
owner: K. Tanaka
former-id: SYS-7PADSD
parent: REQ-H9113WA
order: b2R
links:
  - type: refines
    target: REQ-Z2QF8WD
    confirmed: 44235e2789f0
---
The secure boot shall restore error conditions in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly using AES-256-GCM
- No error entries in the device log
