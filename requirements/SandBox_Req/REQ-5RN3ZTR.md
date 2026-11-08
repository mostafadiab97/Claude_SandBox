---
id: REQ-5RN3ZTR
type: system-requirement
title: Device registry authenticates sensor readings
status: Approved
priority: Low
owner: Y. Saber
tags:
  - customer-request
  - power
  - release-1.0
former-id: SYS-GBTGV5
parent: REQ-RE9ZKHF
order: b20
links:
  - type: refines
    target: REQ-6WXSS37
    confirmed: 34735dce772b
---
The device registry shall detect relay events using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly for at least 10 years
- No error entries in the device log
