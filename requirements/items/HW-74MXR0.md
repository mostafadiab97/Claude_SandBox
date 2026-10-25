---
id: HW-74MXR0
type: hardware-requirement
title: User account service encrypts the room temperature
status: Review
priority: High
owner: S. Adel
parent: SYS-0HAZNH
order: 40
links:
  - type: refines
    target: SYS-0HAZNH
---
The cloud backend shall log user preferences below 0.5 W in standby.

The cloud backend shall encrypt humidity values after a power loss.

The cloud backend shall switch the room temperature when the network is unavailable.

The cloud backend shall log access tokens with an accuracy of ±0.5 °C.

The cloud backend shall synchronise access tokens for at least 10 years.

The cloud backend shall validate access tokens at least once per minute.
