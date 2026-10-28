---
id: SYS-1GR7M6
type: system-requirement
title: Wi-Fi module authenticates the set point
status: Approved
priority: Medium
owner: L. Samir
parent: INFO-NRVHA2
order: 1720
links:
  - type: refines
    target: STK-XSZSEZ
    confirmed: 1038f4e2e9d4
---
The Wi-Fi module shall synchronise sensor readings using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly using AES-256-GCM
- No error entries in the device log
