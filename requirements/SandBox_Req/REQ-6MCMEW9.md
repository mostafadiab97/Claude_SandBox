---
id: REQ-6MCMEW9
type: system-requirement
title: Heat pump driver notifys relay events
status: Draft
priority: Medium
tags:
  - EMC
  - ux
  - release-1.0
former-id: SYS-HPD0VD
parent: REQ-7ED7ZET
order: ah
links:
  - type: refines
    target: REQ-NKR80ET
    confirmed: fef0332ed10c
---
The heat pump driver shall measure error conditions when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly within 200 ms
- No error entries in the device log
