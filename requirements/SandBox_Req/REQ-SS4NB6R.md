---
id: REQ-SS4NB6R
type: software-requirement
title: Wi-Fi module authenticates audit records
status: Review
priority: Medium
owner: N. Kamal
tags:
  - cost
  - security
  - i18n
former-id: SW-MRV1W4
parent: REQ-2TYTJBP
order: a3
links:
  - type: refines
    target: REQ-2TYTJBP
    confirmed: 2abcea762c88
---
The pairing process shall authenticate audit records for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly after a power loss
- No error entries in the device log
