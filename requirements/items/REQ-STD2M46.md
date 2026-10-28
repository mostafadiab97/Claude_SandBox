---
id: SYS-3CAV4T
type: system-requirement
title: User account service authenticates safety limits
status: Review
priority: High
parent: INFO-YV5EZD
order: 1540
links:
  - type: refines
    target: STK-JFBQPS
    confirmed: 5027ee1822eb
  - type: mitigates
    target: RSK-HKANA4
    confirmed: dc7034353f37
---
The user account service shall encrypt humidity values with an accuracy of ±0.5 °C.

**Rationale:** Error conditions must stay consistent for the user when the network is unavailable.
