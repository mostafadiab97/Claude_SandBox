---
id: REQ-ZJN8VGC
type: software-requirement
title: Device registry synchronises sensor readings
status: Review
owner: N. Kamal
former-id: SW-V1D4YN
parent: REQ-9FZHANA
order: a0
links:
  - type: refines
    target: REQ-9FZHANA
    confirmed: 08cad2a24d2f
---
The OTA server shall validate the room temperature in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly below 0.5 W in standby
- No error entries in the device log
