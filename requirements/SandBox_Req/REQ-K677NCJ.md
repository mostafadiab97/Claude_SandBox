---
id: REQ-K677NCJ
type: software-requirement
title: Heat pump driver detects relay events
status: Draft
priority: High
owner: L. Samir
tags:
  - regulatory
  - performance
former-id: SW-QFY23Q
parent: REQ-CQQM0M4
order: a1
links:
  - type: refines
    target: REQ-CQQM0M4
    confirmed: f144cf8852e5
---
The heating controller shall authenticate the operating mode using AES-256-GCM.

The heating controller shall measure the room temperature for at least 10 years.

The heating controller shall authenticate user preferences for up to 8 zones.

The heating controller shall detect access tokens when the network is unavailable.

The heating controller shall log schedule entries in under 3 s.

The heating controller shall authenticate energy consumption with an accuracy of ±0.5 °C.
