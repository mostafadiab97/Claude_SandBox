---
id: REQ-K40ETXP
type: software-requirement
title: Cloud backend restores user preferences
status: Approved
priority: Medium
owner: N. Kamal
tags:
  - customer-request
former-id: SW-4EB74B
parent: REQ-3558H8N
order: a1
links:
  - type: refines
    target: REQ-3558H8N
    confirmed: 33b1a201b47a
---
The telemetry pipeline shall limit the connection state at least once per minute.

The telemetry pipeline shall limit the connection state using AES-256-GCM.

The telemetry pipeline shall authenticate sensor readings at least once per minute.

The telemetry pipeline shall measure sensor readings after a power loss.

The telemetry pipeline shall encrypt sensor readings with an accuracy of ±0.5 °C.

The telemetry pipeline shall validate schedule entries for at least 10 years.
