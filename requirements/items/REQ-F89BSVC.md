---
id: REQ-F89BSVC
type: software-requirement
title: Status LED notifys humidity values
status: Review
priority: Medium
owner: K. Tanaka
former-id: SW-BHPCQG
parent: REQ-SH3K9A3
order: a1
links:
  - type: refines
    target: REQ-SH3K9A3
    confirmed: 38b79a7f1e8e
---
The backlight shall store the connection state with an accuracy of ±0.5 °C.

The backlight shall switch the set point below 0.5 W in standby.

The backlight shall notify sensor readings using AES-256-GCM.

The backlight shall limit error conditions with an accuracy of ±0.5 °C.

The backlight shall calibrate humidity values when the network is unavailable.

The backlight shall log the set point within 200 ms.
