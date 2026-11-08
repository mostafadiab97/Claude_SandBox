---
id: REQ-C547WF3
type: software-requirement
title: Heating controller authenticates access tokens
status: Draft
priority: Medium
owner: H. Mostafa
former-id: SW-FC71ZM
parent: REQ-TR67EMJ
order: a1
links:
  - type: refines
    target: REQ-TR67EMJ
    confirmed: 1e93aa64c8e1
---
The heat pump driver shall switch humidity values below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly using AES-256-GCM
- No error entries in the device log
