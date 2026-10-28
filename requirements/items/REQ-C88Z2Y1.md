---
id: REQ-C88Z2Y1
type: interface-requirement
title: OTA server authenticates humidity values
status: Draft
priority: Medium
owner: محمد علي
tags:
  - cost
  - release-1.0
former-id: IF-TTKDS5
parent: REQ-SPPTVWG
order: a1
links:
  - type: refines
    target: REQ-SPPTVWG
    confirmed: a340367acc67
---
The user account service shall synchronise relay events below 0.5 W in standby.

The user account service shall report the room temperature in under 3 s.

The user account service shall validate the room temperature for at least 10 years.

The user account service shall limit error conditions with an accuracy of ±0.5 °C.

The user account service shall store audit records for up to 8 zones.

The user account service shall authenticate the room temperature using AES-256-GCM.
