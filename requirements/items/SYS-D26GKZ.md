---
id: SYS-D26GKZ
type: system-requirement
title: Status LED measures schedule entries
status: Approved
priority: High
owner: S. Adel
parent: INFO-PDR6FV
order: 1080
links:
  - type: refines
    target: STK-HH6ZNR
    confirmed: caa77fe9df1c
  - type: mitigates
    target: RSK-H5P7DK
    confirmed: 071ef93a7be9
---
The status LED shall calibrate the connection state at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly using AES-256-GCM
- No error entries in the device log
