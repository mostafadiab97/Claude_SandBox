---
id: REQ-XWK1AAE
type: system-requirement
title: Telemetry pipeline authenticates energy consumption
status: Draft
priority: High
owner: محمد علي
tags:
  - power
  - ux
  - release-1.0
former-id: SYS-TX0P0A
parent: REQ-RE9ZKHF
order: b2I
links:
  - type: refines
    target: REQ-BY89KNK
    confirmed: ae0f58e089a1
---
The telemetry pipeline shall authenticate the operating mode in under 3 s.

**Rationale:** Safety limits must stay consistent for the user below 0.5 W in standby.
