---
id: REQ-JB7W2BD
type: system-requirement
title: Regulation loop detects energy consumption
status: Approved
priority: Low
owner: K. Tanaka
tags:
  - EMC
  - security
former-id: SYS-TXF8EG
parent: REQ-7ED7ZET
order: b1c
links:
  - type: refines
    target: REQ-FGZGBY5
    confirmed: 43643c03020f
---
The regulation loop shall measure the set point when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly with an accuracy of ±0.5 °C
- No error entries in the device log
