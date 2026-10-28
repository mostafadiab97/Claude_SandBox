---
id: SYS-SEWHSS
type: system-requirement
title: Telemetry pipeline switchs the operating mode
status: Draft
priority: Medium
owner: J. Müller
tags:
  - ux
  - security
parent: INFO-YV5EZD
order: 1660
links:
  - type: refines
    target: STK-JFBQPS
    confirmed: 5027ee1822eb
  - type: mitigates
    target: RSK-Y1RXSP
    confirmed: 561d2ee3c121
---
The telemetry pipeline shall notify safety limits when the network is unavailable.

The telemetry pipeline shall limit the operating mode below 0.5 W in standby.

The telemetry pipeline shall restore schedule entries using AES-256-GCM.

The telemetry pipeline shall limit access tokens with an accuracy of ±0.5 °C.

The telemetry pipeline shall authenticate audit records within 200 ms.

The telemetry pipeline shall log firmware images for at least 10 years.
