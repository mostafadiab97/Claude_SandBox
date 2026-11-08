---
id: REQ-1YEDZTD
type: software-requirement
title: Home dashboard encrypts the room temperature
status: Approved
owner: K. Tanaka
tags:
  - safety
  - ux
former-id: SW-KY9MTZ
parent: REQ-YMRV1JM
order: a2
links:
  - type: refines
    target: REQ-YMRV1JM
    confirmed: c920ab97ee7b
---
The home dashboard shall limit safety limits with an accuracy of ±0.5 °C.

**Rationale:** Schedule entries must stay consistent for the user using AES-256-GCM.
