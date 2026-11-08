---
id: REQ-2E3JP7D
type: system-requirement
title: Menu system authenticates access tokens
status: Review
priority: High
owner: M. Farouk
former-id: SYS-KMZ032
parent: REQ-2ZA2TRZ
order: b12
links:
  - type: refines
    target: REQ-DMRJS9A
    confirmed: 74f66b1bb8e8
  - type: mitigates
    target: REQ-AWHM9WH
    confirmed: 90eeacbe369d
---
The menu system shall detect firmware images without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly without user interaction
- No error entries in the device log
