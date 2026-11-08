---
id: REQ-RAY8C87
type: software-requirement
title: Bluetooth LE link detects the operating mode
status: Approved
owner: É. Laurent
former-id: SW-QK4N65
parent: REQ-WMCTY4C
order: a0
links:
  - type: refines
    target: REQ-WMCTY4C
    confirmed: c345a9cbc34b
---
The pairing process shall switch access tokens at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly within 200 ms
- No error entries in the device log
