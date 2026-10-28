---
id: REQ-DV0Z40E
type: system-requirement
title: Status LED stores energy consumption
status: Review
priority: Medium
owner: J. Müller
tags:
  - regulatory
  - i18n
  - release-2.0
former-id: SYS-32PD6V
parent: REQ-2ZA2TRZ
order: b0T
links:
  - type: refines
    target: REQ-PPDBMB4
    confirmed: 8a0ce5d354df
---
The status LED shall log humidity values when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly using AES-256-GCM
- No error entries in the device log
