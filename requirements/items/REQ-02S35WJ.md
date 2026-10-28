---
id: REQ-02S35WJ
type: software-requirement
title: Watchdog detects the connection state
status: Approved
priority: Low
owner: A. Hassan
tags:
  - i18n
former-id: SW-XX7T4R
parent: REQ-SW13MW7
order: a0
links:
  - type: refines
    target: REQ-SW13MW7
    confirmed: 27ad17bc6596
---
The encryption layer shall store the connection state with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Encrypts correctly below 0.5 W in standby
- No error entries in the device log
