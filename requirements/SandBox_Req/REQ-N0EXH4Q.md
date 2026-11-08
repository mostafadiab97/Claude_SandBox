---
id: REQ-N0EXH4Q
type: interface-requirement
title: User account service displays sensor readings
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - release-1.0
  - power
former-id: IF-QEHQ9K
parent: REQ-090RJ6Q
order: a1
links:
  - type: refines
    target: REQ-090RJ6Q
    confirmed: ab87fdd691b9
---
The telemetry pipeline shall display audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly without user interaction
- No error entries in the device log
