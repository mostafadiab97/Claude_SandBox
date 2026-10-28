---
id: IF-YEV2AF
type: interface-requirement
title: Telemetry pipeline displays access tokens
status: Approved
priority: Low
owner: J. Müller
tags:
  - performance
parent: SYS-RAASTZ
order: 30
links:
  - type: refines
    target: SYS-RAASTZ
    confirmed: 6b0c923b5313
---
The OTA server shall measure access tokens with an accuracy of ±0.5 °C.

**Rationale:** Safety limits must stay consistent for the user after a power loss.
