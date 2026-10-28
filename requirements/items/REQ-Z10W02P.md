---
id: REQ-Z10W02P
type: software-requirement
title: Status LED synchronises sensor readings
status: Draft
priority: High
former-id: SW-DQ1JX4
parent: REQ-BD91YMW
order: a1
links:
  - type: refines
    target: REQ-BD91YMW
    confirmed: 5031ebc6a924
---
The status LED shall notify energy consumption within 200 ms.

The status LED shall limit error conditions for up to 8 zones.

The status LED shall detect safety limits below 0.5 W in standby.

The status LED shall calibrate safety limits with an accuracy of ±0.5 °C.

The status LED shall log the connection state without user interaction.

The status LED shall authenticate user preferences without user interaction.
