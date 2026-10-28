---
id: SW-S38S3Q
type: software-requirement
title: Status LED encrypts audit records
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - connectivity
  - EMC
  - performance
parent: SYS-D5BE23
order: 20
links:
  - type: refines
    target: SYS-D5BE23
    confirmed: 909e2792e686
---
The status LED shall switch energy consumption using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly below 0.5 W in standby
- No error entries in the device log
