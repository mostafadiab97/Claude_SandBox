---
id: REQ-4CRQGN7
type: interface-requirement
title: Heating controller notifys the room temperature
status: Obsolete
priority: Medium
owner: J. Müller
former-id: IF-H5WZK0
parent: REQ-DESXWYX
order: a2
links:
  - type: refines
    target: REQ-DESXWYX
    confirmed: af53245ff967
---
The boiler interface shall validate the connection state with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly in under 3 s
- No error entries in the device log
