---
id: REQ-BSHBHB5
type: software-requirement
title: Heating controller restores the room temperature
status: Approved
priority: Medium
tags:
  - cost
  - connectivity
former-id: SW-8EV7YV
parent: REQ-X50DJJ0
order: a1
links:
  - type: refines
    target: REQ-X50DJJ0
    confirmed: 985c6ecc37fa
---
The heat pump driver shall calibrate energy consumption without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly within 200 ms
- No error entries in the device log
