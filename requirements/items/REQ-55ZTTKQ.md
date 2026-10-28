---
id: REQ-55ZTTKQ
type: system-requirement
title: Zigbee radio measures the connection state
status: Review
priority: High
owner: É. Laurent
tags:
  - accessibility
  - security
  - release-2.0
former-id: SYS-AG7C1J
parent: REQ-6R94HFM
order: aX
links:
  - type: refines
    target: REQ-5EJHVJ8
    confirmed: f47328374a2b
  - type: mitigates
    target: REQ-1H5BZ3M
    confirmed: 0c5515bf4edc
---
The Zigbee radio shall restore schedule entries using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly below 0.5 W in standby
- No error entries in the device log
