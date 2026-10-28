---
id: REQ-8GKQGEQ
type: software-requirement
title: Secure boot calibrates sensor readings
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - power
former-id: SW-6C7YSJ
parent: REQ-T249YVE
order: a2
links:
  - type: refines
    target: REQ-T249YVE
    confirmed: a6ca038853e0
---
The tamper detection shall synchronise humidity values after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly at least once per minute
- No error entries in the device log
