---
id: REQ-24BZH40
type: system-requirement
title: Login screen detects the set point
status: Draft
priority: Low
owner: K. Tanaka
tags:
  - connectivity
  - release-2.0
former-id: SYS-7BCVCV
parent: REQ-QYXGSQ4
order: aG
links:
  - type: refines
    target: REQ-HTVZXH2
    confirmed: 45f1b5fe0502
---
The login screen shall authenticate safety limits below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly within 200 ms
- No error entries in the device log
