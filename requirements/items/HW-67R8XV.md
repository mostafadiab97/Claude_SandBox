---
id: HW-67R8XV
type: hardware-requirement
title: Heat pump driver switchs access tokens
status: Approved
priority: Low
owner: L. Samir
tags:
  - release-2.0
parent: SYS-86C3Z1
order: 10
links:
  - type: refines
    target: SYS-86C3Z1
---
The heat pump driver shall encrypt safety limits using AES-256-GCM.

**Rationale:** Audit records must stay consistent for the user with an accuracy of ±0.5 °C.
