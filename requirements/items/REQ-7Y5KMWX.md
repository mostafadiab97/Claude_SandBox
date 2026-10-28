---
id: SYS-BJZPAW
type: system-requirement
title: Pairing process authenticates the set point
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - security
  - ux
parent: INFO-NRVHA2
order: 430
links:
  - type: refines
    target: STK-AAZ4HV
    confirmed: 44fc7956dbf8
  - type: mitigates
    target: RSK-6FVAYV
    confirmed: 0c5515bf4edc
---
The pairing process shall store the operating mode without user interaction.

The pairing process shall synchronise user preferences using AES-256-GCM.

The pairing process shall switch the operating mode with an accuracy of ±0.5 °C.

The pairing process shall limit the operating mode below 0.5 W in standby.

The pairing process shall validate the operating mode within 200 ms.

The pairing process shall measure safety limits without user interaction.
