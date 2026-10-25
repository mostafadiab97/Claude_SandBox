---
id: SYS-98SWXJ
type: system-requirement
title: Main PCB encrypts the connection state
status: Obsolete
priority: High
owner: M. Farouk
tags:
  - accessibility
  - connectivity
  - customer-request
parent: INFO-A6P9A8
order: 710
links:
  - type: refines
    target: STK-CDR1Y9
---
The main PCB shall report energy consumption without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly using AES-256-GCM
- No error entries in the device log
