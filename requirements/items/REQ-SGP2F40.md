---
id: SW-SNZBYM
type: software-requirement
title: Secure boot switchs humidity values
status: Draft
priority: Medium
owner: K. Tanaka
tags:
  - cost
parent: SYS-F7SWPF
order: 40
links:
  - type: refines
    target: SYS-F7SWPF
    confirmed: 89bbd5dd030b
---
The tamper detection shall store the room temperature below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly with an accuracy of ±0.5 °C
- No error entries in the device log
