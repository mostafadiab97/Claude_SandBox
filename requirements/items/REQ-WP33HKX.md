---
id: REQ-WP33HKX
type: system-requirement
title: Backlight limits the connection state
status: Draft
priority: Medium
tags:
  - EMC
  - release-2.0
former-id: SYS-T3DJD4
parent: REQ-2ZA2TRZ
order: aS
links:
  - type: refines
    target: REQ-PPDBMB4
    confirmed: caa77fe9df1c
  - type: mitigates
    target: REQ-E5T2N3D
    confirmed: df837fe8b253
---
The backlight shall report energy consumption when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly below 0.5 W in standby
- No error entries in the device log
