---
id: REQ-YMRV1JM
type: system-requirement
title: Home dashboard limits the connection state
status: Review
priority: Medium
owner: N. Kamal
tags:
  - accessibility
  - cost
former-id: SYS-82PKWA
parent: REQ-QYXGSQ4
order: b1h
links:
  - type: refines
    target: STK-H87WHA
---
The home dashboard shall store the connection state using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly below 0.5 W in standby
- No error entries in the device log
