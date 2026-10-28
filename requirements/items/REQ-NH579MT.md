---
id: REQ-NH579MT
type: system-requirement
title: Tamper detection calibrates safety limits
status: Approved
priority: Medium
former-id: SYS-XM6K6N
parent: REQ-H9113WA
order: b1F
links:
  - type: refines
    target: REQ-9YG77WV
    confirmed: 080168ea99ae
---
The tamper detection shall calibrate the set point using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly below 0.5 W in standby
- No error entries in the device log
