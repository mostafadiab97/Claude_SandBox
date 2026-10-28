---
id: REQ-8XAB9X3
type: system-requirement
title: Zone valve validates error conditions
status: Approved
owner: R. Nabil
tags:
  - customer-request
former-id: SYS-7THG7S
parent: REQ-7ED7ZET
order: aU
links:
  - type: refines
    target: REQ-6WZCEAT
    confirmed: fc922ec1a72e
  - type: mitigates
    target: REQ-9NWZEMH
    confirmed: 0db3fa8291ee
---
The zone valve shall log energy consumption using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly within 200 ms
- No error entries in the device log
