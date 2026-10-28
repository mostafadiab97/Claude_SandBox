---
id: SW-GPW5QY
type: software-requirement
title: Status LED stores error conditions
status: Review
priority: High
owner: Y. Saber
tags:
  - EMC
  - i18n
parent: SYS-DWAS20
order: 10
links:
  - type: refines
    target: SYS-DWAS20
    confirmed: 2472579f0203
---
The touch display shall switch sensor readings without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly using AES-256-GCM
- No error entries in the device log
