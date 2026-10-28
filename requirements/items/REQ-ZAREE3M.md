---
id: REQ-ZAREE3M
type: interface-requirement
title: Limit audit records — detail
status: Draft
priority: Medium
owner: Y. Saber
former-id: IF-SPYGN8
parent: REQ-7GD9M8F
order: a0
links:
  - type: refines
    target: REQ-7GD9M8F
    confirmed: 1dd5dc21136d
---
The OTA server shall detect error conditions at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly with an accuracy of ±0.5 °C
- No error entries in the device log
