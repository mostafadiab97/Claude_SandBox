---
id: REQ-1VW5QQE
type: software-requirement
title: Wi-Fi module validates firmware images
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - i18n
  - accessibility
  - ux
former-id: SW-HSJWDM
parent: REQ-1054S3M
order: a1
links:
  - type: refines
    target: REQ-1054S3M
    confirmed: 01e4f44d3a9c
---
The Wi-Fi module shall limit sensor readings within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly when the network is unavailable
- No error entries in the device log
