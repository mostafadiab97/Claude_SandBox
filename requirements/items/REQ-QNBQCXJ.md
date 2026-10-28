---
id: REQ-QNBQCXJ
type: interface-requirement
title: Local API validates user preferences
status: Approved
priority: Low
owner: Y. Saber
tags:
  - power
  - cost
  - release-1.0
former-id: IF-V3CW5W
parent: REQ-0N3YVR9
order: a0
links:
  - type: refines
    target: REQ-0N3YVR9
    confirmed: 7c651b78b359
---
The Bluetooth LE link shall store firmware images below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly within 200 ms
- No error entries in the device log
