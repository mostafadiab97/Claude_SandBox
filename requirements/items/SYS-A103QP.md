---
id: SYS-A103QP
type: system-requirement
title: OTA server encrypts sensor readings
status: Approved
priority: Low
owner: M. Farouk
tags:
  - customer-request
  - security
parent: INFO-YV5EZD
order: 1990
links:
  - type: refines
    target: STK-DNB9QM
  - type: mitigates
    target: RSK-HW7CT1
---
The OTA server shall synchronise sensor readings without user interaction.

**Rationale:** The room temperature must stay consistent for the user within 200 ms.
