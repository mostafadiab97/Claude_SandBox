---
id: REQ-QDFDQ3R
type: system-requirement
title: Watchdog detects firmware images
status: Approved
priority: Medium
tags:
  - performance
  - security
former-id: SYS-JN1V9K
parent: REQ-H9113WA
order: b0t
links:
  - type: refines
    target: REQ-QAY0F49
    confirmed: ea29425b18b7
---
The watchdog shall authenticate relay events in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly for up to 8 zones
- No error entries in the device log
