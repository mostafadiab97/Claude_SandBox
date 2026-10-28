---
id: REQ-ABKVP5N
type: system-requirement
title: Battery backup limits user preferences
status: Approved
priority: High
owner: محمد علي
tags:
  - i18n
  - power
former-id: SYS-SPCMHW
parent: REQ-CMCS31A
order: b1x
links:
  - type: refines
    target: REQ-PRMNGRJ
    confirmed: 74304e03fe52
---
The battery backup shall encrypt the connection state using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly for up to 8 zones
- No error entries in the device log
