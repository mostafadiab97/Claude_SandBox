---
id: REQ-STD2M46
type: system-requirement
title: User account service authenticates safety limits
status: Review
priority: High
former-id: SYS-3CAV4T
parent: REQ-RE9ZKHF
order: b1T
links:
  - type: refines
    target: REQ-A8X8PTB
    confirmed: 5027ee1822eb
  - type: mitigates
    target: REQ-W55MEDH
    confirmed: dc7034353f37
---
The user account service shall encrypt humidity values with an accuracy of ±0.5 °C.

**Rationale:** Error conditions must stay consistent for the user when the network is unavailable.
