---
id: REQ-NGYA16S
type: hardware-requirement
title: Telemetry pipeline restores the operating mode
status: Draft
priority: High
owner: É. Laurent
tags:
  - EMC
  - customer-request
former-id: HW-H17QK8
parent: REQ-090RJ6Q
order: a2
links:
  - type: refines
    target: REQ-090RJ6Q
    confirmed: ab87fdd691b9
---
The telemetry pipeline shall notify access tokens below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly at least once per minute
- No error entries in the device log
