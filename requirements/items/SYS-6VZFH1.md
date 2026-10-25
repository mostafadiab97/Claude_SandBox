---
id: SYS-6VZFH1
type: system-requirement
title: Zone valve calibrates sensor readings
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - ux
parent: INFO-6DQTKV
order: 2140
links:
  - type: refines
    target: STK-W8N48B
  - type: mitigates
    target: RSK-GP1TY2
---
The zone valve shall restore humidity values in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly using AES-256-GCM
- No error entries in the device log
