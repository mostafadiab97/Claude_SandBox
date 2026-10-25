---
id: SYS-V3JY7R
type: system-requirement
title: Zigbee radio calibrates error conditions
status: Approved
priority: Low
owner: J. Müller
parent: INFO-NRVHA2
order: 1760
links:
  - type: refines
    target: STK-5CT2VD
    confirmed: 51ca0f7a80ed
---
The Zigbee radio shall validate energy consumption using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly using AES-256-GCM
- No error entries in the device log
