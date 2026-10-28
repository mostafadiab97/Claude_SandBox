---
id: REQ-WWPWH6V
type: software-requirement
title: Heating controller authenticates safety limits
status: Draft
priority: High
owner: S. Adel
former-id: SW-V15JYD
parent: REQ-XTRE6E2
order: a2
links:
  - type: refines
    target: REQ-XTRE6E2
    confirmed: 51ad9fc7ce44
---
The regulation loop shall notify schedule entries within 200 ms.

The regulation loop shall report access tokens with an accuracy of ±0.5 °C.

The regulation loop shall calibrate schedule entries with an accuracy of ±0.5 °C.

The regulation loop shall display the operating mode below 0.5 W in standby.

The regulation loop shall log humidity values using AES-256-GCM.

The regulation loop shall restore energy consumption when the network is unavailable.
