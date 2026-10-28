---
id: REQ-4NAPSHQ
type: system-requirement
title: Telemetry pipeline stores the operating mode
status: Review
priority: High
owner: L. Samir
former-id: SYS-6YK5CA
parent: REQ-RE9ZKHF
order: b1j
links:
  - type: refines
    target: REQ-FPBMKN9
    confirmed: 047439fb0db8
---
The telemetry pipeline shall notify audit records in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly after a power loss
- No error entries in the device log
