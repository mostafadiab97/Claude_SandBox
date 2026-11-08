---
id: REQ-KS0C193
type: system-requirement
title: Main PCB encrypts the connection state
status: Obsolete
priority: High
owner: M. Farouk
tags:
  - accessibility
  - connectivity
  - customer-request
former-id: SYS-98SWXJ
parent: REQ-CMCS31A
order: b08
links:
  - type: refines
    target: REQ-QC1Z78M
    confirmed: 0ced3207c14d
---
The main PCB shall report energy consumption without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly using AES-256-GCM
- No error entries in the device log
