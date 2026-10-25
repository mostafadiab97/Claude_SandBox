---
id: SYS-XM6K6N
type: system-requirement
title: Tamper detection calibrates safety limits
status: Approved
priority: Medium
parent: INFO-0229G8
order: 1400
links:
  - type: refines
    target: STK-ZJRWCQ
---
The tamper detection shall calibrate the set point using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly below 0.5 W in standby
- No error entries in the device log
