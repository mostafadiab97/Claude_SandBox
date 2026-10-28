---
id: REQ-PEZVNGX
type: interface-requirement
title: Tamper detection calibrates audit records
status: Draft
priority: Medium
owner: محمد علي
tags:
  - customer-request
  - accessibility
former-id: IF-RA09AE
parent: REQ-MND8W5P
order: a0
links:
  - type: refines
    target: REQ-MND8W5P
    confirmed: 12c71184dbf6
---
The secure boot shall detect audit records with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly within 200 ms
- No error entries in the device log
