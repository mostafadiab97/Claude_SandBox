---
id: REQ-MKJBG9X
type: system-requirement
title: Boiler interface switchs relay events
status: Review
priority: High
owner: R. Nabil
tags:
  - release-1.0
  - accessibility
former-id: SYS-0P0DNN
parent: REQ-7ED7ZET
order: b17
links:
  - type: refines
    target: REQ-Q1KNR7Q
    confirmed: 25b39ad8cae7
  - type: mitigates
    target: REQ-7T4HD7G
    confirmed: a62dde39783d
---
The boiler interface shall encrypt the room temperature after a power loss.

**Rationale:** The connection state must stay consistent for the user with an accuracy of ±0.5 °C.
