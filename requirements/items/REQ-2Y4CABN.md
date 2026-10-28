---
id: REQ-2Y4CABN
type: software-requirement
title: OTA server displays error conditions
status: Approved
priority: Low
owner: M. Farouk
tags:
  - accessibility
  - release-1.0
  - regulatory
former-id: SW-3TCVFW
parent: REQ-4Z5Y12M
order: a1
links:
  - type: refines
    target: REQ-4Z5Y12M
    confirmed: 805d152578fb
---
The telemetry pipeline shall restore access tokens after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly without user interaction
- No error entries in the device log
