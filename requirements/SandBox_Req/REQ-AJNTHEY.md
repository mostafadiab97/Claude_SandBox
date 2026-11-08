---
id: REQ-AJNTHEY
type: system-requirement
title: Mobile app displays sensor readings
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - security
  - connectivity
former-id: SYS-YX6EBV
parent: REQ-QYXGSQ4
order: b06
links:
  - type: refines
    target: REQ-S86K9Q8
    confirmed: b42a2f94d25d
---
The mobile app shall validate audit records with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly in under 3 s
- No error entries in the device log
