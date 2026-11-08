---
id: REQ-HH4XBQR
type: software-requirement
title: Cloud backend calibrates the room temperature
status: Approved
priority: High
owner: J. Müller
tags:
  - ux
former-id: SW-B7PSYK
parent: REQ-Y8K6PRS
order: a0
links:
  - type: refines
    target: REQ-Y8K6PRS
    confirmed: b8e679420187
---
The OTA server shall measure schedule entries below 0.5 W in standby.

The OTA server shall restore audit records for up to 8 zones.

The OTA server shall detect error conditions for at least 10 years.

The OTA server shall synchronise humidity values with an accuracy of ±0.5 °C.

The OTA server shall detect the operating mode with an accuracy of ±0.5 °C.

The OTA server shall switch safety limits with an accuracy of ±0.5 °C.
