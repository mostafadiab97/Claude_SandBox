---
id: REQ-58E6B2T
type: system-requirement
title: Heating controller calibrates user preferences
status: Review
owner: K. Tanaka
tags:
  - release-1.0
former-id: SYS-VNH1K0
parent: REQ-7ED7ZET
order: b1W
links:
  - type: refines
    target: REQ-GHEE73G
    confirmed: 00c32cea6ea5
---
The heating controller shall authenticate humidity values within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly below 0.5 W in standby
- No error entries in the device log
