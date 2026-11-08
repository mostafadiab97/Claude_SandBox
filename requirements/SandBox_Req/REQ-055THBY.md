---
id: REQ-055THBY
type: system-requirement
title: Status LED measures schedule entries
status: Approved
priority: High
owner: S. Adel
former-id: SYS-D26GKZ
parent: REQ-2ZA2TRZ
order: b0j
links:
  - type: refines
    target: REQ-PPDBMB4
    confirmed: caa77fe9df1c
  - type: mitigates
    target: REQ-19NM7SG
    confirmed: 071ef93a7be9
---
The status LED shall calibrate the connection state at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly using AES-256-GCM
- No error entries in the device log
