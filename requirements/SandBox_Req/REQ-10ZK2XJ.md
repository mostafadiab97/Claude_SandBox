---
id: REQ-10ZK2XJ
type: system-requirement
title: Secure boot logs the connection state
status: Approved
priority: High
owner: Y. Saber
former-id: SYS-W77D8P
parent: REQ-H9113WA
order: b1b
links:
  - type: refines
    target: REQ-AVJ6PR8
    confirmed: fc1f05b44684
  - type: mitigates
    target: REQ-G4DF4P0
    confirmed: fdd2a6f94f2a
---
The secure boot shall notify humidity values in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly within 200 ms
- No error entries in the device log
