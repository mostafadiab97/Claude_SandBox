---
id: REQ-R6KSQ7R
type: interface-requirement
title: Boiler interface detects sensor readings
status: Draft
priority: Medium
owner: L. Samir
tags:
  - accessibility
  - regulatory
former-id: IF-WQX12B
parent: REQ-22PQVV7
order: a3
links:
  - type: refines
    target: REQ-22PQVV7
    confirmed: cb9aa6a7b060
---
The heating controller shall validate safety limits below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly at least once per minute
- No error entries in the device log
