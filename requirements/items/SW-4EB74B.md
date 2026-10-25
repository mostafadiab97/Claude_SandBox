---
id: SW-4EB74B
type: software-requirement
title: Cloud backend restores user preferences
status: Approved
priority: Medium
owner: N. Kamal
tags:
  - customer-request
parent: SYS-77PVXT
order: 20
links:
  - type: refines
    target: SYS-77PVXT
    confirmed: 33b1a201b47a
---
The telemetry pipeline shall limit the connection state at least once per minute.

The telemetry pipeline shall limit the connection state using AES-256-GCM.

The telemetry pipeline shall authenticate sensor readings at least once per minute.

The telemetry pipeline shall measure sensor readings after a power loss.

The telemetry pipeline shall encrypt sensor readings with an accuracy of ±0.5 °C.

The telemetry pipeline shall validate schedule entries for at least 10 years.
