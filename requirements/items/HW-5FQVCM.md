---
id: HW-5FQVCM
type: hardware-requirement
title: Battery backup reports access tokens
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - performance
  - release-2.0
parent: SYS-HRRNGW
order: 10
links:
  - type: refines
    target: SYS-HRRNGW
    confirmed: afbcfeedc1e2
---
The power supply shall measure humidity values when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly after a power loss
- No error entries in the device log
