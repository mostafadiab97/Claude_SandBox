---
id: REQ-Y9FVQ7Q
type: system-requirement
title: OTA server encrypts sensor readings
status: Approved
priority: Low
owner: M. Farouk
tags:
  - customer-request
  - security
former-id: SYS-A103QP
parent: REQ-RE9ZKHF
order: b2C
links:
  - type: refines
    target: REQ-VPP3H2E
    confirmed: 90394ce55463
  - type: mitigates
    target: REQ-2XXW52D
    confirmed: 9979c7ab202d
---
The OTA server shall synchronise sensor readings without user interaction.

**Rationale:** The room temperature must stay consistent for the user within 200 ms.
