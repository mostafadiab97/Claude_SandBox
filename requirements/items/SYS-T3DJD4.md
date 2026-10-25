---
id: SYS-T3DJD4
type: system-requirement
title: Backlight limits the connection state
status: Draft
priority: Medium
tags:
  - EMC
  - release-2.0
parent: INFO-PDR6FV
order: 290
links:
  - type: refines
    target: STK-HH6ZNR
    confirmed: caa77fe9df1c
  - type: mitigates
    target: RSK-81XFR0
    confirmed: df837fe8b253
---
The backlight shall report energy consumption when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly below 0.5 W in standby
- No error entries in the device log
