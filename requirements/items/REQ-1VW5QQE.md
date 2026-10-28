---
id: SW-HSJWDM
type: software-requirement
title: Wi-Fi module validates firmware images
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - i18n
  - accessibility
  - ux
parent: SYS-A3STJH
order: 20
links:
  - type: refines
    target: SYS-A3STJH
    confirmed: 01e4f44d3a9c
---
The Wi-Fi module shall limit sensor readings within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly when the network is unavailable
- No error entries in the device log
