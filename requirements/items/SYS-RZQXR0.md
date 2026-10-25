---
id: SYS-RZQXR0
type: system-requirement
title: Secure boot displays firmware images
status: Draft
priority: High
owner: J. Müller
tags:
  - security
  - customer-request
  - EMC
parent: INFO-0229G8
order: 970
links:
  - type: refines
    target: STK-G2H1B9
    confirmed: fce33b342585
  - type: mitigates
    target: RSK-RV8KBD
    confirmed: 637ec5e39d53
---
The secure boot shall limit error conditions using AES-256-GCM.

**Rationale:** User preferences must stay consistent for the user using AES-256-GCM.
