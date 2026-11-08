---
id: REQ-0J0KCAB
type: interface-requirement
title: Battery backup stores firmware images
status: Draft
tags:
  - customer-request
  - performance
former-id: IF-50VFAS
parent: REQ-YSKYE18
order: a3
links:
  - type: refines
    target: REQ-YSKYE18
    confirmed: f0923cc9ca25
---
The power supply shall switch relay events when the network is unavailable.

The power supply shall limit relay events within 200 ms.

The power supply shall report the connection state in all supported languages.

The power supply shall store sensor readings at least once per minute.

The power supply shall calibrate relay events using AES-256-GCM.

The power supply shall display the set point below 0.5 W in standby.
