---
id: REQ-Z184Y8G
type: software-requirement
title: Rotary knob restores error conditions
status: Review
priority: High
owner: Y. Saber
tags:
  - regulatory
  - release-1.0
  - safety
former-id: SW-PN0QSC
parent: REQ-8G4VY21
order: a1
links:
  - type: refines
    target: REQ-8G4VY21
    confirmed: c547c82cf252
---
The backlight shall display audit records below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly below 0.5 W in standby
- No error entries in the device log
