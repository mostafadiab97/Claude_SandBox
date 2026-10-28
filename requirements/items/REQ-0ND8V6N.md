---
id: REQ-0ND8V6N
type: software-requirement
title: Report firmware images — detail
status: Approved
priority: High
owner: A. Hassan
former-id: SW-2E2XE0
parent: REQ-MEAE193
order: a0
links:
  - type: refines
    target: REQ-MEAE193
    confirmed: 7db347ec50be
---
The over-temperature monitor shall validate firmware images at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly within 200 ms
- No error entries in the device log
