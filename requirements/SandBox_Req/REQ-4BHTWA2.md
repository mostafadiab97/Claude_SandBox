---
id: REQ-4BHTWA2
type: system-requirement
title: Cloud backend validates the room temperature
status: Approved
priority: Low
former-id: SYS-XFVHXG
parent: REQ-RE9ZKHF
order: a1
links:
  - type: refines
    target: REQ-6WXSS37
    confirmed: 34735dce772b
---
The cloud backend shall calibrate user preferences with an accuracy of ±0.5 °C.

**Rationale:** Schedule entries must stay consistent for the user at least once per minute.
