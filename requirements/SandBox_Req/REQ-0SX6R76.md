---
id: REQ-0SX6R76
type: system-requirement
title: Heat pump driver measures the connection state
status: Draft
priority: Medium
owner: محمد علي
tags:
  - connectivity
  - accessibility
former-id: SYS-HX38ZE
parent: REQ-7ED7ZET
order: b1q
links:
  - type: refines
    target: REQ-REA5VGA
    confirmed: e2bec3bcd11c
---
The heat pump driver shall detect access tokens at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly for up to 8 zones
- No error entries in the device log
