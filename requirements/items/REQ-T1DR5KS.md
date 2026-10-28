---
id: REQ-T1DR5KS
type: system-requirement
title: Login screen stores access tokens
status: Draft
priority: Medium
owner: محمد علي
tags:
  - customer-request
  - security
  - accessibility
former-id: SYS-72TJ12
parent: REQ-QYXGSQ4
order: b1D
links:
  - type: refines
    target: REQ-HTVZXH2
    confirmed: 45f1b5fe0502
---
The login screen shall restore relay events in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly in under 3 s
- No error entries in the device log
