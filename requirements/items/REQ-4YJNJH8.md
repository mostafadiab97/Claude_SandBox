---
id: REQ-4YJNJH8
type: system-requirement
title: Tamper detection restores the connection state
status: Approved
owner: R. Nabil
tags:
  - release-1.0
  - performance
former-id: SYS-BQJJNH
parent: REQ-H9113WA
order: aP
links:
  - type: refines
    target: REQ-GCMD4T5
    confirmed: bcce6e51beb4
---
The tamper detection shall measure firmware images after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly after a power loss
- No error entries in the device log
