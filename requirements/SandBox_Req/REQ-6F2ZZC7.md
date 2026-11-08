---
id: REQ-6F2ZZC7
type: system-requirement
title: Battery backup stores safety limits
status: Approved
owner: Y. Saber
tags:
  - release-2.0
  - security
  - release-1.0
former-id: SYS-HEVMYH
parent: REQ-CMCS31A
order: b17
links:
  - type: refines
    target: REQ-Z62Y5S5
    confirmed: 9c3c4f9c0995
---
The battery backup shall detect the connection state using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly with an accuracy of ±0.5 °C
- No error entries in the device log
