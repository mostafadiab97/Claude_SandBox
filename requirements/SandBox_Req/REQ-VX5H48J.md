---
id: REQ-VX5H48J
type: software-requirement
title: OTA server authenticates error conditions
status: Approved
priority: Medium
owner: J. Müller
former-id: SW-XF8FA2
parent: REQ-ZWGY9CP
order: a0
links:
  - type: refines
    target: REQ-ZWGY9CP
    confirmed: 95dd5bc85d61
---
The device registry shall validate the operating mode after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly with an accuracy of ±0.5 °C
- No error entries in the device log
