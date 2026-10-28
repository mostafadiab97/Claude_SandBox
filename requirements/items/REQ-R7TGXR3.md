---
id: REQ-R7TGXR3
type: software-requirement
title: Tamper detection validates user preferences
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - performance
  - cost
  - release-2.0
former-id: SW-TBE47G
parent: REQ-RSNHK9N
order: a2
links:
  - type: refines
    target: REQ-RSNHK9N
    confirmed: 061c07f59466
---
The encryption layer shall log user preferences with an accuracy of ±0.5 °C.

**Rationale:** Sensor readings must stay consistent for the user at least once per minute.
