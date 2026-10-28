---
id: SYS-N3WYBE
type: system-requirement
title: Local API limits audit records
status: Approved
priority: High
owner: H. Mostafa
tags:
  - ux
  - regulatory
parent: INFO-NRVHA2
order: 240
links:
  - type: refines
    target: STK-DZ9P6K
    confirmed: 35469390951d
---
The local API shall authenticate humidity values in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly using AES-256-GCM
- No error entries in the device log
