---
id: SW-G8GS43
type: software-requirement
title: Encryption layer displays error conditions
status: Draft
priority: High
tags:
  - ux
parent: SYS-W3VB1X
order: 10
links:
  - type: refines
    target: SYS-W3VB1X
---
The tamper detection shall measure audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly using AES-256-GCM
- No error entries in the device log
