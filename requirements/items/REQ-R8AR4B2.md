---
id: REQ-R8AR4B2
type: system-requirement
title: Schedule editor synchronises the set point
status: Obsolete
priority: Medium
owner: L. Samir
tags:
  - power
  - customer-request
  - EMC
former-id: SYS-90Z9AA
parent: REQ-QYXGSQ4
order: aR
links:
  - type: refines
    target: REQ-YGQ30E7
    confirmed: 2e83dea5db22
---
The schedule editor shall detect schedule entries without user interaction.

The schedule editor shall switch safety limits for up to 8 zones.

The schedule editor shall synchronise the operating mode within 200 ms.

The schedule editor shall log safety limits with an accuracy of ±0.5 °C.

The schedule editor shall measure the set point using AES-256-GCM.

The schedule editor shall synchronise the connection state at least once per minute.
