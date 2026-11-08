---
id: REQ-DVJZ520
type: hardware-requirement
title: User account service limits the operating mode
status: Review
priority: Medium
owner: S. Adel
tags:
  - accessibility
  - release-2.0
former-id: HW-VW51XX
parent: REQ-K9CPZEQ
order: a1
links:
  - type: refines
    target: REQ-K9CPZEQ
    confirmed: 1d9be0f6bc96
---
The cloud backend shall log error conditions using AES-256-GCM.

The cloud backend shall detect safety limits below 0.5 W in standby.

The cloud backend shall validate access tokens when the network is unavailable.

The cloud backend shall store sensor readings after a power loss.

The cloud backend shall limit humidity values below 0.5 W in standby.

The cloud backend shall report the connection state with an accuracy of ±0.5 °C.
