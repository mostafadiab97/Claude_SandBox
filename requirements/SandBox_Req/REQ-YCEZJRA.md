---
id: REQ-YCEZJRA
type: software-requirement
title: User account service synchronises the connection state
status: Draft
owner: R. Nabil
tags:
  - safety
former-id: SW-79R9ZE
parent: REQ-J43HRVN
order: a0
links:
  - type: refines
    target: REQ-J43HRVN
    confirmed: 36aae11cfefa
---
The telemetry pipeline shall validate access tokens in under 3 s.

**Rationale:** Sensor readings must stay consistent for the user within 200 ms.
