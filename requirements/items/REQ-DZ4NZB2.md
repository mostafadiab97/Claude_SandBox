---
id: REQ-DZ4NZB2
type: system-requirement
title: Regulation loop switchs the room temperature
status: Draft
priority: High
owner: N. Kamal
former-id: SYS-FMTYXJ
parent: REQ-7ED7ZET
order: b22
links:
  - type: refines
    target: REQ-NKR80ET
    confirmed: fef0332ed10c
  - type: mitigates
    target: REQ-95C6RSR
    confirmed: 84e686f1bbcc
---
The regulation loop shall calibrate access tokens below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly at least once per minute
- No error entries in the device log
