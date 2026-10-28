---
id: REQ-C9JBZJ5
type: interface-requirement
title: Local API reports humidity values
status: Draft
owner: H. Mostafa
tags:
  - connectivity
  - release-1.0
former-id: IF-C38JY4
parent: REQ-J216NC7
order: a1
links:
  - type: refines
    target: REQ-J216NC7
    confirmed: 5bd6f55bad83
---
The Bluetooth LE link shall display the connection state with an accuracy of ±0.5 °C.

The Bluetooth LE link shall store the set point below 0.5 W in standby.

The Bluetooth LE link shall notify the room temperature below 0.5 W in standby.

The Bluetooth LE link shall report sensor readings below 0.5 W in standby.

The Bluetooth LE link shall restore the operating mode at least once per minute.

The Bluetooth LE link shall calibrate schedule entries for up to 8 zones.
