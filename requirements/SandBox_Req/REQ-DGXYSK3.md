---
id: REQ-DGXYSK3
type: software-requirement
title: Heat pump driver limits the connection state
status: Draft
owner: A. Hassan
tags:
  - EMC
former-id: SW-YSKNAQ
parent: REQ-6JJPX7J
order: a0
links:
  - type: refines
    target: REQ-6JJPX7J
    confirmed: 6eadc6d38c4a
---
The heat pump driver shall report the connection state below 0.5 W in standby.

**Rationale:** Sensor readings must stay consistent for the user with an accuracy of ±0.5 °C.
