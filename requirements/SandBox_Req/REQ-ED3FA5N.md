---
id: REQ-ED3FA5N
type: hardware-requirement
title: Heat pump driver switchs access tokens
status: Approved
priority: Low
owner: L. Samir
tags:
  - release-2.0
former-id: HW-67R8XV
parent: REQ-EDB3M6H
order: a0
links:
  - type: refines
    target: REQ-EDB3M6H
    confirmed: 9813f1ce92fd
---
The heat pump driver shall encrypt safety limits using AES-256-GCM.

**Rationale:** Audit records must stay consistent for the user with an accuracy of ±0.5 °C.
