---
id: IF-RA09AE
type: interface-requirement
title: Tamper detection calibrates audit records
status: Draft
priority: Medium
owner: محمد علي
tags:
  - customer-request
  - accessibility
parent: SYS-4MWCBY
order: 10
links:
  - type: refines
    target: SYS-4MWCBY
---
The secure boot shall detect audit records with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly within 200 ms
- No error entries in the device log
