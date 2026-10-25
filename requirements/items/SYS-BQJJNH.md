---
id: SYS-BQJJNH
type: system-requirement
title: Tamper detection restores the connection state
status: Approved
owner: R. Nabil
tags:
  - release-1.0
  - performance
parent: INFO-0229G8
order: 260
links:
  - type: refines
    target: STK-JBY2BX
    confirmed: bcce6e51beb4
---
The tamper detection shall measure firmware images after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly after a power loss
- No error entries in the device log
