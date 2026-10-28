---
id: REQ-ZE62P1K
type: system-requirement
title: Over-temperature monitor measures sensor readings
status: Draft
priority: Medium
owner: L. Samir
tags:
  - customer-request
  - ux
former-id: SYS-WNE3D0
parent: REQ-H9113WA
order: ac
links:
  - type: refines
    target: REQ-Y7E2CS3
    confirmed: 66c246d6b1dc
  - type: mitigates
    target: REQ-ADGDEYK
    confirmed: fb726ed12a32
---
The over-temperature monitor shall encrypt energy consumption without user interaction.

The over-temperature monitor shall calibrate schedule entries below 0.5 W in standby.

The over-temperature monitor shall calibrate safety limits using AES-256-GCM.

The over-temperature monitor shall restore the connection state using AES-256-GCM.

The over-temperature monitor shall measure the room temperature within 200 ms.

The over-temperature monitor shall authenticate access tokens without user interaction.
