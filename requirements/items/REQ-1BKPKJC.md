---
id: REQ-1BKPKJC
type: interface-requirement
title: Detect safety limits — detail
status: Draft
priority: Medium
tags:
  - safety
  - accessibility
former-id: IF-N1V23M
parent: REQ-0DAFDZD
order: a0
links:
  - type: refines
    target: REQ-0DAFDZD
    confirmed: ac310fecb043
---
The heat pump driver shall display the operating mode within 200 ms.

The heat pump driver shall authenticate the operating mode using AES-256-GCM.

The heat pump driver shall log error conditions within 200 ms.

The heat pump driver shall validate user preferences without user interaction.

The heat pump driver shall notify sensor readings after a power loss.

The heat pump driver shall store relay events with an accuracy of ±0.5 °C.
