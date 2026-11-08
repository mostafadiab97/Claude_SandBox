---
id: REQ-PP7B9AP
type: software-requirement
title: Pairing process calibrates safety limits
status: Approved
priority: High
owner: R. Nabil
former-id: SW-SPY8J5
parent: REQ-7Y5KMWX
order: a0
links:
  - type: refines
    target: REQ-7Y5KMWX
    confirmed: 118d961f538b
---
The pairing process shall switch the set point at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly using AES-256-GCM
- No error entries in the device log
