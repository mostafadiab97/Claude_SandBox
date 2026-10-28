---
id: REQ-QXV8HKB
type: hardware-requirement
title: User account service encrypts the room temperature
status: Review
priority: High
owner: S. Adel
former-id: HW-74MXR0
parent: REQ-YP9B1S9
order: a3
links:
  - type: refines
    target: REQ-YP9B1S9
    confirmed: 8fef3f917b7b
---
The cloud backend shall log user preferences below 0.5 W in standby.

The cloud backend shall encrypt humidity values after a power loss.

The cloud backend shall switch the room temperature when the network is unavailable.

The cloud backend shall log access tokens with an accuracy of ±0.5 °C.

The cloud backend shall synchronise access tokens for at least 10 years.

The cloud backend shall validate access tokens at least once per minute.
