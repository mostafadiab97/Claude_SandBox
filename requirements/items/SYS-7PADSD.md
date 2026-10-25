---
id: SYS-7PADSD
type: system-requirement
title: Secure boot authenticates firmware images
status: Approved
priority: High
owner: K. Tanaka
parent: INFO-0229G8
order: 2140
links:
  - type: refines
    target: STK-SM9B7Z
    confirmed: 44235e2789f0
---
The secure boot shall restore error conditions in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly using AES-256-GCM
- No error entries in the device log
