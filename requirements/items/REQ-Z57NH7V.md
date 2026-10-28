---
id: REQ-Z57NH7V
type: software-requirement
title: Over-temperature monitor encrypts safety limits
status: Draft
priority: High
owner: K. Tanaka
tags:
  - safety
  - release-1.0
former-id: SW-AB0MZ2
parent: REQ-VKX7BXX
order: a3
links:
  - type: refines
    target: REQ-VKX7BXX
    confirmed: 1c27482f8c01
---
The secure boot shall validate safety limits with an accuracy of ±0.5 °C.

**Rationale:** Firmware images must stay consistent for the user using AES-256-GCM.
