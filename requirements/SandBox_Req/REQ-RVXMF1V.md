---
id: REQ-RVXMF1V
type: system-requirement
title: Device registry stores the connection state
status: Approved
priority: Low
owner: S. Adel
tags:
  - connectivity
former-id: SYS-YWXHFA
parent: REQ-RE9ZKHF
order: b1V
links:
  - type: refines
    target: REQ-FPBMKN9
    confirmed: 047439fb0db8
---
The device registry shall store error conditions with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly using AES-256-GCM
- No error entries in the device log
