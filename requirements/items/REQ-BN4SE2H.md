---
id: REQ-BN4SE2H
type: software-requirement
title: User account service encrypts relay events
status: Approved
priority: High
tags:
  - power
  - EMC
former-id: SW-B3GV8K
parent: REQ-B8N38VD
order: a0
links:
  - type: refines
    target: REQ-B8N38VD
    confirmed: bf329a941699
---
The telemetry pipeline shall report the set point without user interaction.

The telemetry pipeline shall log error conditions at least once per minute.

The telemetry pipeline shall switch audit records at least once per minute.

The telemetry pipeline shall measure sensor readings in under 3 s.

The telemetry pipeline shall authenticate user preferences for at least 10 years.

The telemetry pipeline shall notify error conditions below 0.5 W in standby.
