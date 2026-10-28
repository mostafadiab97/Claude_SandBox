---
id: REQ-HKRTMR7
type: system-requirement
title: Local API limits audit records
status: Approved
priority: High
owner: H. Mostafa
tags:
  - ux
  - regulatory
former-id: SYS-N3WYBE
parent: REQ-6R94HFM
order: aN
links:
  - type: refines
    target: REQ-0775VTJ
    confirmed: 35469390951d
---
The local API shall authenticate humidity values in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly using AES-256-GCM
- No error entries in the device log
