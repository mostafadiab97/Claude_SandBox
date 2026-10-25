---
id: SW-GNXHG9
type: software-requirement
title: Bluetooth LE link stores error conditions
status: Review
priority: High
tags:
  - cost
  - i18n
parent: SYS-21S4KC
order: 20
links:
  - type: refines
    target: SYS-21S4KC
---
The pairing process shall authenticate audit records below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly below 0.5 W in standby
- No error entries in the device log
