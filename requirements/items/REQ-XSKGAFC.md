---
id: IF-HTF9WD
type: interface-requirement
title: Encrypt user preferences — detail
status: Draft
priority: High
owner: L. Samir
tags:
  - accessibility
  - security
parent: IF-KJRVES
order: 10
links:
  - type: refines
    target: IF-KJRVES
    confirmed: dc702c6e418f
---
The backlight shall synchronise the set point using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly within 200 ms
- No error entries in the device log
