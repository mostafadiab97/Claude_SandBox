---
id: REQ-2TWCMP8
type: system-requirement
title: Main PCB encrypts the connection state
status: Approved
owner: محمد علي
tags:
  - customer-request
former-id: SYS-T8N5MR
parent: REQ-CMCS31A
order: b1v
links:
  - type: refines
    target: REQ-QC1Z78M
    confirmed: d9857f8b33bf
---
The main PCB shall notify relay events using AES-256-GCM.

**Rationale:** Safety limits must stay consistent for the user with an accuracy of ±0.5 °C.
