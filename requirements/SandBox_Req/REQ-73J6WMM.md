---
id: REQ-73J6WMM
type: system-requirement
title: Boiler interface synchronises audit records
status: Approved
priority: High
tags:
  - release-1.0
former-id: SYS-3FCPBN
parent: REQ-7ED7ZET
order: ai
links:
  - type: refines
    target: REQ-FGZGBY5
    confirmed: 43643c03020f
---
The boiler interface shall calibrate access tokens within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly after a power loss
- No error entries in the device log
