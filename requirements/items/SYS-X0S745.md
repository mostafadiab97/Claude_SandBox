---
id: SYS-X0S745
type: system-requirement
title: Watchdog encrypts sensor readings
status: Approved
priority: Medium
owner: L. Samir
tags:
  - safety
parent: INFO-0229G8
order: 730
links:
  - type: refines
    target: STK-SZWQ0A
    confirmed: fc1f05b44684
  - type: mitigates
    target: RSK-4K4PV0
    confirmed: a3307c1a9b06
---
The watchdog shall report the set point using AES-256-GCM.
