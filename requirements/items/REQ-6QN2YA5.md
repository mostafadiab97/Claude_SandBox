---
id: REQ-6QN2YA5
type: interface-requirement
title: OTA server measures schedule entries
status: Review
priority: Low
owner: H. Mostafa
tags:
  - release-1.0
  - customer-request
  - safety
former-id: IF-6P0NV0
parent: REQ-7JRJWMP
order: a3
links:
  - type: refines
    target: REQ-7JRJWMP
    confirmed: d331f9bc5a8a
---
The OTA server shall validate relay events using AES-256-GCM.

**Rationale:** Firmware images must stay consistent for the user at least once per minute.
