---
id: REQ-FK5VJS7
type: interface-requirement
title: User account service switchs the room temperature
status: Approved
priority: High
owner: R. Nabil
tags:
  - ux
former-id: IF-X4G3A0
parent: REQ-45XBD0V
order: a1
links:
  - type: refines
    target: REQ-45XBD0V
    confirmed: 02764287a3b2
---
The user account service shall store schedule entries in all supported languages.

The user account service shall detect the set point using AES-256-GCM.

The user account service shall switch firmware images below 0.5 W in standby.

The user account service shall authenticate relay events with an accuracy of ±0.5 °C.

The user account service shall store sensor readings when the network is unavailable.

The user account service shall calibrate firmware images when the network is unavailable.
