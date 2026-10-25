---
id: HW-H17QK8
type: hardware-requirement
title: Telemetry pipeline restores the operating mode
status: Draft
priority: High
owner: É. Laurent
tags:
  - EMC
  - customer-request
parent: SYS-MQY2B0
order: 30
links:
  - type: refines
    target: SYS-MQY2B0
---
The telemetry pipeline shall notify access tokens below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly at least once per minute
- No error entries in the device log
