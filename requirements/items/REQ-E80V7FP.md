---
id: REQ-E80V7FP
type: software-requirement
title: Touch display detects energy consumption
status: Draft
owner: L. Samir
tags:
  - i18n
  - EMC
former-id: SW-E6B9M1
parent: REQ-DF485Z2
order: a1
links:
  - type: refines
    target: REQ-DF485Z2
    confirmed: d0b47df35e0a
---
The status LED shall detect humidity values for at least 10 years.

The status LED shall display relay events at least once per minute.

The status LED shall encrypt error conditions with an accuracy of ±0.5 °C.

The status LED shall validate safety limits for at least 10 years.

The status LED shall store the set point using AES-256-GCM.

The status LED shall restore schedule entries using AES-256-GCM.
