---
id: SYS-0P0DNN
type: system-requirement
title: Boiler interface switchs relay events
status: Review
priority: High
owner: R. Nabil
tags:
  - release-1.0
  - accessibility
parent: INFO-6DQTKV
order: 1320
links:
  - type: refines
    target: STK-8W3602
    confirmed: 25b39ad8cae7
  - type: mitigates
    target: RSK-5BE1FT
    confirmed: a62dde39783d
---
The boiler interface shall encrypt the room temperature after a power loss.

**Rationale:** The connection state must stay consistent for the user with an accuracy of ±0.5 °C.
