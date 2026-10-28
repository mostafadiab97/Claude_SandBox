---
id: SW-FC71ZM
type: software-requirement
title: Heating controller authenticates access tokens
status: Draft
priority: Medium
owner: H. Mostafa
parent: SYS-VNKX29
order: 20
links:
  - type: refines
    target: SYS-VNKX29
    confirmed: 1e93aa64c8e1
---
The heat pump driver shall switch humidity values below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly using AES-256-GCM
- No error entries in the device log
