---
id: REQ-WMGY1VS
type: system-requirement
title: Heating controller notifys access tokens
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - release-2.0
  - i18n
former-id: SYS-Y0VFQW
parent: REQ-7ED7ZET
order: a3
links:
  - type: refines
    target: REQ-Q1KNR7Q
    confirmed: 25b39ad8cae7
  - type: mitigates
    target: REQ-N90PXTW
    confirmed: dd1f8627cbb6
---
The heating controller shall notify relay events within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly using AES-256-GCM
- No error entries in the device log
