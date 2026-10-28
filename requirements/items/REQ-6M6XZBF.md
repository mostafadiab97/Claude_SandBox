---
id: SW-APJKM4
type: software-requirement
title: Bluetooth LE link switchs sensor readings
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - security
  - customer-request
  - release-2.0
parent: SYS-DNKAZZ
order: 40
links:
  - type: refines
    target: SYS-DNKAZZ
    confirmed: 22452286eeb7
---
The local API shall report relay events within 200 ms.

**Rationale:** Firmware images must stay consistent for the user in under 3 s.
