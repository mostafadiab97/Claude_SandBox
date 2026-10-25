---
id: SYS-HPD0VD
type: system-requirement
title: Heat pump driver notifys relay events
status: Draft
priority: Medium
tags:
  - EMC
  - ux
  - release-1.0
parent: INFO-6DQTKV
order: 440
links:
  - type: refines
    target: STK-75QZSA
    confirmed: b8a4c00165fe
---
The heat pump driver shall measure error conditions when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly within 200 ms
- No error entries in the device log
