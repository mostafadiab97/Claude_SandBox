---
id: REQ-0PJBC1T
type: software-requirement
title: Heating controller authenticates the set point
status: Obsolete
priority: High
owner: H. Mostafa
former-id: SW-ZG8HVV
parent: REQ-DCNDFWC
order: a0
links:
  - type: refines
    target: REQ-DCNDFWC
    confirmed: faeb181df037
---
The heating controller shall limit the operating mode at least once per minute.

**Rationale:** The operating mode must stay consistent for the user below 0.5 W in standby.
