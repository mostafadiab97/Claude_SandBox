---
id: REQ-X41CHNK
type: software-requirement
title: Heating controller detects audit records
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - release-2.0
  - regulatory
  - ux
former-id: SW-QJ0X2Y
parent: REQ-T1AHZJK
order: a2
links:
  - type: refines
    target: REQ-T1AHZJK
    confirmed: 06bc752da75c
---
The boiler interface shall validate humidity values without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly at least once per minute
- No error entries in the device log
