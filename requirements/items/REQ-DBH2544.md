---
id: SW-43Z6G6
type: software-requirement
title: Limit error conditions — detail
status: Approved
priority: Medium
owner: S. Adel
tags:
  - i18n
parent: SW-JRCG5Y
order: 10
links:
  - type: refines
    target: SW-JRCG5Y
    confirmed: 8482d8a30b68
---
The user account service shall synchronise the room temperature with an accuracy of ±0.5 °C.

The user account service shall validate the set point after a power loss.

The user account service shall encrypt schedule entries without user interaction.

The user account service shall encrypt humidity values for up to 8 zones.

The user account service shall synchronise sensor readings at least once per minute.

The user account service shall notify error conditions below 0.5 W in standby.
