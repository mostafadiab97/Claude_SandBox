---
id: SYS-Y0VFQW
type: system-requirement
title: Heating controller notifys access tokens
status: Draft
priority: Medium
owner: A. Hassan
tags:
  - release-2.0
  - i18n
parent: INFO-6DQTKV
order: 40
links:
  - type: refines
    target: STK-8W3602
    confirmed: 25b39ad8cae7
  - type: mitigates
    target: RSK-G8ARKV
    confirmed: dd1f8627cbb6
---
The heating controller shall notify relay events within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly using AES-256-GCM
- No error entries in the device log
