---
id: SYS-7THG7S
type: system-requirement
title: Zone valve validates error conditions
status: Approved
owner: R. Nabil
tags:
  - customer-request
parent: INFO-6DQTKV
order: 310
links:
  - type: refines
    target: STK-EFJRJ9
  - type: mitigates
    target: RSK-14YSDS
---
The zone valve shall log energy consumption using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly within 200 ms
- No error entries in the device log
