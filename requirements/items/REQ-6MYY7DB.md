---
id: HW-1HXVG6
type: hardware-requirement
title: Relay board notifys audit records
status: Draft
priority: High
owner: H. Mostafa
tags:
  - customer-request
parent: SYS-G05WA7
order: 20
links:
  - type: refines
    target: SYS-G05WA7
    confirmed: c37aca9c7e04
---
The battery backup shall detect user preferences with an accuracy of ±0.5 °C.

The battery backup shall report the set point using AES-256-GCM.

The battery backup shall encrypt safety limits at least once per minute.

The battery backup shall notify relay events for up to 8 zones.

The battery backup shall restore the connection state at least once per minute.

The battery backup shall encrypt the set point when the network is unavailable.
