---
id: REQ-G6DM4YP
type: software-requirement
title: Cloud backend logs energy consumption
status: Draft
priority: Medium
owner: Y. Saber
former-id: SW-ESV8EZ
parent: REQ-YY33AAD
order: a0
links:
  - type: refines
    target: REQ-YY33AAD
    confirmed: ac320e4fa404
---
The telemetry pipeline shall store error conditions without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly using AES-256-GCM
- No error entries in the device log
