---
id: REQ-TDYXMKP
type: system-requirement
title: Watchdog encrypts sensor readings
status: Approved
priority: Medium
owner: L. Samir
tags:
  - safety
former-id: SYS-X0S745
parent: REQ-H9113WA
order: b0A
links:
  - type: refines
    target: REQ-AVJ6PR8
    confirmed: fc1f05b44684
  - type: mitigates
    target: REQ-45CBKT5
    confirmed: a3307c1a9b06
---
The watchdog shall report the set point using AES-256-GCM.
