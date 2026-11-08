---
id: REQ-JG21K63
type: software-requirement
title: Boiler interface calibrates user preferences
status: Approved
priority: High
owner: É. Laurent
former-id: SW-2C9HYA
parent: REQ-GHCFENA
order: a3
links:
  - type: refines
    target: REQ-GHCFENA
    confirmed: 705a530b1b5d
---
The heat pump driver shall authenticate the connection state below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly without user interaction
- No error entries in the device log
