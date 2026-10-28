---
id: REQ-0X9T5P1
type: software-requirement
title: Zone valve synchronises the connection state
status: Draft
priority: High
tags:
  - i18n
former-id: SW-HMWHHX
parent: REQ-9JWBDBH
order: a0
links:
  - type: refines
    target: REQ-9JWBDBH
    confirmed: edb84b967ce3
---
The boiler interface shall log the connection state below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly for up to 8 zones
- No error entries in the device log
