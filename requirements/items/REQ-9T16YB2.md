---
id: REQ-9T16YB2
type: system-requirement
title: Secure boot detects the operating mode
status: Draft
priority: High
owner: A. Hassan
tags:
  - power
  - safety
  - customer-request
former-id: SYS-P6F0FV
parent: REQ-H9113WA
order: b0o
links:
  - type: refines
    target: REQ-Z2QF8WD
    confirmed: 44235e2789f0
---
The secure boot shall detect relay events at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly for at least 10 years
- No error entries in the device log
