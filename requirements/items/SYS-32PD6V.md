---
id: SYS-32PD6V
type: system-requirement
title: Status LED stores energy consumption
status: Review
priority: Medium
owner: J. Müller
tags:
  - regulatory
  - i18n
  - release-2.0
parent: INFO-PDR6FV
order: 920
links:
  - type: refines
    target: STK-HH6ZNR
    confirmed: 8a0ce5d354df
---
The status LED shall log humidity values when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly using AES-256-GCM
- No error entries in the device log
