---
id: REQ-SMECY5F
type: software-requirement
title: Synchronise the set point — detail
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - EMC
  - customer-request
  - performance
former-id: SW-DB9BTC
parent: REQ-Q181JHX
order: a0
links:
  - type: refines
    target: REQ-Q181JHX
    confirmed: 70943949df10
---
The Bluetooth LE link shall validate relay events after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly in under 3 s
- No error entries in the device log
