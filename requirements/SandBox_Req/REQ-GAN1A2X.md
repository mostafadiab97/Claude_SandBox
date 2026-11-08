---
id: REQ-GAN1A2X
type: system-requirement
title: Local API authenticates humidity values
status: Approved
priority: High
owner: R. Nabil
tags:
  - power
  - cost
former-id: SYS-ZKTQQ8
parent: REQ-6R94HFM
order: aQ
links:
  - type: refines
    target: REQ-GXR8KE5
    confirmed: fee0d3303478
---
The local API shall calibrate the connection state when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly within 200 ms
- No error entries in the device log
