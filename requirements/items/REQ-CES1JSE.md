---
id: SYS-2NJC1D
type: system-requirement
title: User account service restores schedule entries
status: Review
priority: Medium
owner: S. Adel
parent: INFO-YV5EZD
order: 1960
links:
  - type: refines
    target: STK-DKX022
    confirmed: a534e573be6a
  - type: mitigates
    target: RSK-Y1RXSP
    confirmed: 561d2ee3c121
---
The user account service shall synchronise the room temperature within 200 ms.

**Rationale:** Humidity values must stay consistent for the user with an accuracy of ±0.5 °C.
