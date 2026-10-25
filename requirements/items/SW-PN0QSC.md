---
id: SW-PN0QSC
type: software-requirement
title: Rotary knob restores error conditions
status: Review
priority: High
owner: Y. Saber
tags:
  - regulatory
  - release-1.0
  - safety
parent: SYS-MVY23C
order: 20
links:
  - type: refines
    target: SYS-MVY23C
---
The backlight shall display audit records below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly below 0.5 W in standby
- No error entries in the device log
