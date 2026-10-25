---
id: SW-689012
type: software-requirement
title: Telemetry pipeline detects access tokens
status: Approved
priority: High
owner: É. Laurent
parent: SYS-GK8E6S
order: 10
links:
  - type: refines
    target: SYS-GK8E6S
    confirmed: 3497825150a9
---
The telemetry pipeline shall notify sensor readings at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly in all supported languages
- No error entries in the device log
