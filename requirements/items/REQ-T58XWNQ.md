---
id: REQ-T58XWNQ
type: interface-requirement
title: Main PCB synchronises sensor readings
status: Obsolete
owner: M. Farouk
former-id: IF-F09VCZ
parent: REQ-TA12WYD
order: a2
links:
  - type: refines
    target: REQ-TA12WYD
    confirmed: c37aca9c7e04
---
The battery backup shall synchronise audit records within 200 ms.

The battery backup shall log audit records below 0.5 W in standby.

The battery backup shall detect error conditions with an accuracy of ±0.5 °C.

The battery backup shall report relay events below 0.5 W in standby.

The battery backup shall display audit records in under 3 s.

The battery backup shall measure the operating mode using AES-256-GCM.
