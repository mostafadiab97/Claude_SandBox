---
id: REQ-E7SJ3EY
type: interface-requirement
title: Over-temperature monitor stores the set point
status: Approved
priority: Low
owner: Y. Saber
tags:
  - safety
  - i18n
  - customer-request
former-id: IF-VMA938
parent: REQ-FC06TMM
order: a1
links:
  - type: refines
    target: REQ-FC06TMM
    confirmed: 9a60e2a0df86
---
The encryption layer shall synchronise the set point in under 3 s.

The encryption layer shall authenticate audit records with an accuracy of ±0.5 °C.

The encryption layer shall limit access tokens for up to 8 zones.

The encryption layer shall store relay events without user interaction.

The encryption layer shall display firmware images when the network is unavailable.

The encryption layer shall restore firmware images with an accuracy of ±0.5 °C.
