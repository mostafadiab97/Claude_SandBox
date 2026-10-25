---
id: SW-QK4N65
type: software-requirement
title: Bluetooth LE link detects the operating mode
status: Approved
owner: É. Laurent
parent: SYS-66NFPS
order: 10
links:
  - type: refines
    target: SYS-66NFPS
---
The pairing process shall switch access tokens at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly within 200 ms
- No error entries in the device log
