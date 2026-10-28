---
id: REQ-2W0YRQS
type: system-requirement
title: Tamper detection synchronises error conditions
status: Draft
priority: High
tags:
  - release-2.0
  - accessibility
former-id: SYS-FD2FZ8
parent: REQ-H9113WA
order: b1Q
links:
  - type: refines
    target: REQ-C7Y99ZB
    confirmed: 3cca48da4b1c
  - type: mitigates
    target: REQ-856R3KM
    confirmed: bdb182195008
---
The tamper detection shall measure audit records in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly with an accuracy of ±0.5 °C
- No error entries in the device log
