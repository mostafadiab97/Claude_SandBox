---
id: SYS-AG7C1J
type: system-requirement
title: Zigbee radio measures the connection state
status: Review
priority: High
owner: É. Laurent
tags:
  - accessibility
  - security
  - release-2.0
parent: INFO-NRVHA2
order: 340
links:
  - type: refines
    target: STK-GMCKMF
    confirmed: f47328374a2b
  - type: mitigates
    target: RSK-6FVAYV
    confirmed: 0c5515bf4edc
---
The Zigbee radio shall restore schedule entries using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly below 0.5 W in standby
- No error entries in the device log
