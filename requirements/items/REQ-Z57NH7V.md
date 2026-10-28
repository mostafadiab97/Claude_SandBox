---
id: SW-AB0MZ2
type: software-requirement
title: Over-temperature monitor encrypts safety limits
status: Draft
priority: High
owner: K. Tanaka
tags:
  - safety
  - release-1.0
parent: SYS-RZ204B
order: 40
links:
  - type: refines
    target: SYS-RZ204B
    confirmed: 1c27482f8c01
---
The secure boot shall validate safety limits with an accuracy of ±0.5 °C.

**Rationale:** Firmware images must stay consistent for the user using AES-256-GCM.
