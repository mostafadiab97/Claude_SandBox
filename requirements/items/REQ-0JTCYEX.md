---
id: REQ-0JTCYEX
type: system-requirement
title: Tamper detection stores audit records
status: Review
priority: High
owner: محمد علي
tags:
  - security
  - EMC
  - customer-request
former-id: SYS-SAV1GY
parent: REQ-H9113WA
order: as
links:
  - type: refines
    target: REQ-PGNNV26
    confirmed: c19c22627f21
  - type: mitigates
    target: REQ-856R3KM
    confirmed: bdb182195008
---
The tamper detection shall notify error conditions within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly for up to 8 zones
- No error entries in the device log
