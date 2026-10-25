---
id: IF-SVXBJ9
type: interface-requirement
title: Battery backup limits the set point
status: Review
owner: N. Kamal
tags:
  - security
  - i18n
  - release-2.0
parent: SYS-VDRW9V
order: 30
links:
  - type: refines
    target: SYS-VDRW9V
---
The relay board shall restore the room temperature when the network is unavailable.

The relay board shall display the room temperature with an accuracy of ±0.5 °C.

The relay board shall calibrate sensor readings with an accuracy of ±0.5 °C.

The relay board shall log the operating mode within 200 ms.

The relay board shall synchronise sensor readings for up to 8 zones.

The relay board shall limit the set point within 200 ms.
