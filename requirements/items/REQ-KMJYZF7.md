---
id: REQ-KMJYZF7
type: system-requirement
title: OTA server reports the set point
status: Approved
priority: Low
owner: N. Kamal
tags:
  - release-1.0
former-id: SYS-EQ67JM
parent: REQ-RE9ZKHF
order: b1o
links:
  - type: refines
    target: REQ-M17BCB3
    confirmed: ff820400e2f9
---
The OTA server shall measure safety limits below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly using AES-256-GCM
- No error entries in the device log
