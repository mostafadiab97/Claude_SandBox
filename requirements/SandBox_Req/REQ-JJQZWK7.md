---
id: REQ-JJQZWK7
type: hardware-requirement
title: Battery backup reports access tokens
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - performance
  - release-2.0
former-id: HW-5FQVCM
parent: REQ-P7EBBT6
order: a0
links:
  - type: refines
    target: REQ-P7EBBT6
    confirmed: afbcfeedc1e2
---
The power supply shall measure humidity values when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly after a power loss
- No error entries in the device log
