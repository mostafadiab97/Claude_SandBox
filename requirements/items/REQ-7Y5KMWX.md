---
id: REQ-7Y5KMWX
type: system-requirement
title: Pairing process authenticates the set point
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - security
  - ux
former-id: SYS-BJZPAW
parent: REQ-6R94HFM
order: ag
links:
  - type: refines
    target: REQ-M9DYEF5
    confirmed: 44fc7956dbf8
  - type: mitigates
    target: REQ-1H5BZ3M
    confirmed: 0c5515bf4edc
---
The pairing process shall store the operating mode without user interaction.

The pairing process shall synchronise user preferences using AES-256-GCM.

The pairing process shall switch the operating mode with an accuracy of ±0.5 °C.

The pairing process shall limit the operating mode below 0.5 W in standby.

The pairing process shall validate the operating mode within 200 ms.

The pairing process shall measure safety limits without user interaction.
