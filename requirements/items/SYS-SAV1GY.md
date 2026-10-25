---
id: SYS-SAV1GY
type: system-requirement
title: Tamper detection stores audit records
status: Review
priority: High
owner: محمد علي
tags:
  - security
  - EMC
  - customer-request
parent: INFO-0229G8
order: 550
links:
  - type: refines
    target: STK-B4ZH98
  - type: mitigates
    target: RSK-QEHK9Y
---
The tamper detection shall notify error conditions within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly for up to 8 zones
- No error entries in the device log
