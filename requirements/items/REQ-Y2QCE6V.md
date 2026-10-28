---
id: REQ-Y2QCE6V
type: system-requirement
title: Zigbee radio calibrates error conditions
status: Approved
priority: Low
owner: J. Müller
former-id: SYS-V3JY7R
parent: REQ-6R94HFM
order: b1p
links:
  - type: refines
    target: REQ-YDX9MVW
    confirmed: 51ca0f7a80ed
---
The Zigbee radio shall validate energy consumption using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly using AES-256-GCM
- No error entries in the device log
