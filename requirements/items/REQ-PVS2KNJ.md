---
id: REQ-PVS2KNJ
type: system-requirement
title: Bluetooth LE link calibrates the connection state
status: Approved
priority: High
owner: L. Samir
tags:
  - security
former-id: SYS-VD95TW
parent: REQ-6R94HFM
order: b1F
links:
  - type: refines
    target: REQ-GXR8KE5
    confirmed: fee0d3303478
  - type: mitigates
    target: REQ-1H5BZ3M
    confirmed: 0c5515bf4edc
---
The Bluetooth LE link shall validate safety limits for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly in under 3 s
- No error entries in the device log
