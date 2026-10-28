---
id: REQ-AMHVX2H
type: software-requirement
title: Heating controller notifys sensor readings
status: Approved
priority: Low
owner: A. Hassan
tags:
  - safety
former-id: SW-YYD8MJ
parent: REQ-FEE2S5J
order: a1
links:
  - type: refines
    target: REQ-FEE2S5J
    confirmed: 708e0f664c1b
---
The heating controller shall report sensor readings when the network is unavailable.

The heating controller shall measure the operating mode using AES-256-GCM.

The heating controller shall detect audit records within 200 ms.

The heating controller shall calibrate the operating mode without user interaction.

The heating controller shall validate safety limits without user interaction.

The heating controller shall encrypt the operating mode below 0.5 W in standby.
