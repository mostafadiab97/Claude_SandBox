---
id: REQ-Z0DX4ND
type: software-requirement
title: Encryption layer displays the operating mode
status: Review
priority: High
owner: J. Müller
former-id: SW-6431BN
parent: REQ-CKNG4P8
order: a1
links:
  - type: refines
    target: REQ-CKNG4P8
    confirmed: da1b062f4b9e
---
The over-temperature monitor shall encrypt schedule entries using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly within 200 ms
- No error entries in the device log
