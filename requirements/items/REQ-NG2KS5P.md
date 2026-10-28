---
id: REQ-NG2KS5P
type: system-requirement
title: Telemetry pipeline switchs the operating mode
status: Draft
priority: Medium
owner: J. Müller
tags:
  - ux
  - security
former-id: SYS-SEWHSS
parent: REQ-RE9ZKHF
order: b1f
links:
  - type: refines
    target: REQ-A8X8PTB
    confirmed: 5027ee1822eb
  - type: mitigates
    target: REQ-D0C5GC1
    confirmed: 561d2ee3c121
---
The telemetry pipeline shall notify safety limits when the network is unavailable.

The telemetry pipeline shall limit the operating mode below 0.5 W in standby.

The telemetry pipeline shall restore schedule entries using AES-256-GCM.

The telemetry pipeline shall limit access tokens with an accuracy of ±0.5 °C.

The telemetry pipeline shall authenticate audit records within 200 ms.

The telemetry pipeline shall log firmware images for at least 10 years.
