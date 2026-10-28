---
id: IF-XQQZ1E
type: interface-requirement
title: Backlight notifys audit records
status: Review
priority: High
owner: É. Laurent
tags:
  - connectivity
  - release-2.0
parent: SYS-TYCMRT
order: 10
links:
  - type: refines
    target: SYS-TYCMRT
    confirmed: cd494a5f904a
---
The status LED shall display relay events for at least 10 years.

The status LED shall store access tokens at least once per minute.

The status LED shall report error conditions without user interaction.

The status LED shall detect sensor readings for up to 8 zones.

The status LED shall synchronise the connection state with an accuracy of ±0.5 °C.

The status LED shall calibrate firmware images below 0.5 W in standby.
