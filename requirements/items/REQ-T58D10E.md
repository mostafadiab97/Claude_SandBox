---
id: REQ-T58D10E
type: hardware-requirement
title: Boiler interface validates relay events
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - safety
former-id: HW-QXPSXV
parent: REQ-QG4NKYK
order: a2
links:
  - type: refines
    target: REQ-QG4NKYK
    confirmed: 13efe84ae7ac
---
The regulation loop shall authenticate relay events after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly for up to 8 zones
- No error entries in the device log
