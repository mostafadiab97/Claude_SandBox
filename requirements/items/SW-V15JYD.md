---
id: SW-V15JYD
type: software-requirement
title: Heating controller authenticates safety limits
status: Draft
priority: High
owner: S. Adel
parent: SYS-5449PV
order: 30
links:
  - type: refines
    target: SYS-5449PV
---
The regulation loop shall notify schedule entries within 200 ms.

The regulation loop shall report access tokens with an accuracy of ±0.5 °C.

The regulation loop shall calibrate schedule entries with an accuracy of ±0.5 °C.

The regulation loop shall display the operating mode below 0.5 W in standby.

The regulation loop shall log humidity values using AES-256-GCM.

The regulation loop shall restore energy consumption when the network is unavailable.
