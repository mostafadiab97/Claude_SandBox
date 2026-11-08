---
id: REQ-X9Z01C6
type: software-requirement
title: Log access tokens — detail
status: Review
priority: Medium
owner: S. Adel
tags:
  - connectivity
  - performance
former-id: SW-6RS2D2
parent: REQ-9EAJVGZ
order: a0
links:
  - type: refines
    target: REQ-9EAJVGZ
    confirmed: a2de404f9c89
---
The heating controller shall limit sensor readings when the network is unavailable.

The heating controller shall notify safety limits using AES-256-GCM.

The heating controller shall switch energy consumption within 200 ms.

The heating controller shall restore sensor readings using AES-256-GCM.

The heating controller shall notify the operating mode within 200 ms.

The heating controller shall authenticate the room temperature in under 3 s.
