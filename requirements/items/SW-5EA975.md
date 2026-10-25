---
id: SW-5EA975
type: software-requirement
title: Tamper detection logs the room temperature
status: Approved
priority: High
owner: N. Kamal
tags:
  - customer-request
  - security
  - ux
parent: SYS-NVKX9K
order: 40
links:
  - type: refines
    target: SYS-NVKX9K
    confirmed: 720362ab5cfe
---
The over-temperature monitor shall log relay events without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly using AES-256-GCM
- No error entries in the device log
