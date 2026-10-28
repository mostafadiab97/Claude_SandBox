---
id: REQ-2QSCHGK
type: software-requirement
title: Regulation loop logs relay events
status: Approved
priority: Low
tags:
  - performance
former-id: SW-C9V4XY
parent: REQ-JTJVT7P
order: a2
links:
  - type: refines
    target: REQ-JTJVT7P
    confirmed: fb88a89b54aa
---
The heating controller shall notify relay events at least once per minute.

The heating controller shall store error conditions in under 3 s.

The heating controller shall switch humidity values at least once per minute.

The heating controller shall calibrate sensor readings below 0.5 W in standby.

The heating controller shall switch user preferences with an accuracy of ±0.5 °C.

The heating controller shall log the room temperature at least once per minute.
