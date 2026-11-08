---
id: REQ-EZ7D2K2
type: hardware-requirement
title: Zigbee radio detects the room temperature
status: Approved
priority: Low
owner: L. Samir
tags:
  - ux
former-id: HW-NV2BSC
parent: REQ-1K6VZF7
order: a1
links:
  - type: refines
    target: REQ-1K6VZF7
    confirmed: 0ce16e7c9c10
---
The pairing process shall measure the room temperature within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly at least once per minute
- No error entries in the device log
