---
id: REQ-ETWMPXK
type: system-requirement
title: Over-temperature monitor measures the operating mode
status: Draft
priority: Low
owner: M. Farouk
tags:
  - release-2.0
former-id: SYS-47V3JP
parent: REQ-H9113WA
order: b1o
links:
  - type: refines
    target: REQ-375SK1B
    confirmed: ba30e28a130f
  - type: mitigates
    target: REQ-C971M8M
    confirmed: a67337939a06
---
The over-temperature monitor shall limit firmware images for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly using AES-256-GCM
- No error entries in the device log
