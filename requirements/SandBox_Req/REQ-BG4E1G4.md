---
id: REQ-BG4E1G4
type: software-requirement
title: Status LED encrypts audit records
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - connectivity
  - EMC
  - performance
former-id: SW-S38S3Q
parent: REQ-AYKW2SY
order: a1
links:
  - type: refines
    target: REQ-AYKW2SY
    confirmed: 909e2792e686
---
The status LED shall switch energy consumption using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly below 0.5 W in standby
- No error entries in the device log
