---
id: REQ-0XJRDZS
type: software-requirement
title: Telemetry pipeline detects access tokens
status: Approved
priority: High
owner: É. Laurent
former-id: SW-689012
parent: REQ-PRHYJ2F
order: a0
links:
  - type: refines
    target: REQ-PRHYJ2F
    confirmed: 3497825150a9
---
The telemetry pipeline shall notify sensor readings at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly in all supported languages
- No error entries in the device log
