---
id: SYS-QPHFQ7
type: system-requirement
title: Pairing process detects user preferences
status: Approved
priority: High
owner: É. Laurent
tags:
  - security
  - release-1.0
parent: INFO-NRVHA2
order: 2130
links:
  - type: refines
    target: STK-GMCKMF
    confirmed: f47328374a2b
---
The pairing process shall notify error conditions without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly in under 3 s
- No error entries in the device log
