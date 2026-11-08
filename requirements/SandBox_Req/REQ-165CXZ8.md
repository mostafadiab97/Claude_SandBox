---
id: REQ-165CXZ8
type: hardware-requirement
title: Power supply reports sensor readings
status: Draft
priority: Medium
owner: S. Adel
tags:
  - i18n
former-id: HW-Y8D40Y
parent: REQ-YED15DF
order: a0
links:
  - type: refines
    target: REQ-YED15DF
    confirmed: eaf4dadef412
---
The power supply shall detect the room temperature using AES-256-GCM.

The power supply shall encrypt error conditions for at least 10 years.

The power supply shall synchronise sensor readings within 200 ms.

The power supply shall notify firmware images using AES-256-GCM.

The power supply shall calibrate energy consumption below 0.5 W in standby.

The power supply shall store the connection state for up to 8 zones.
