---
id: REQ-SP1KJBX
type: hardware-requirement
title: Zone valve displays safety limits
status: Approved
priority: Low
tags:
  - security
  - safety
  - EMC
former-id: HW-WAGTXW
parent: REQ-QAGJ3HS
order: a0
links:
  - type: refines
    target: REQ-QAGJ3HS
    confirmed: 7162ed5d8a28
---
The zone valve shall encrypt humidity values when the network is unavailable.

The zone valve shall notify humidity values using AES-256-GCM.

The zone valve shall log audit records at least once per minute.

The zone valve shall restore safety limits for up to 8 zones.

The zone valve shall synchronise audit records for at least 10 years.

The zone valve shall notify energy consumption below 0.5 W in standby.
