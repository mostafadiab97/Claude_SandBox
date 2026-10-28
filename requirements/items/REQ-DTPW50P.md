---
id: REQ-DTPW50P
type: system-requirement
title: Secure boot displays firmware images
status: Draft
priority: High
owner: J. Müller
tags:
  - security
  - customer-request
  - EMC
former-id: SYS-RZQXR0
parent: REQ-H9113WA
order: b0Y
links:
  - type: refines
    target: REQ-Q8ZRB9S
    confirmed: fce33b342585
  - type: mitigates
    target: REQ-VYYM5AA
    confirmed: 637ec5e39d53
---
The secure boot shall limit error conditions using AES-256-GCM.

**Rationale:** User preferences must stay consistent for the user using AES-256-GCM.
