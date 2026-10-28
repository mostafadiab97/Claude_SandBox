---
id: REQ-KT0RFX3
type: hardware-requirement
title: Store user preferences — detail
status: Approved
priority: Medium
tags:
  - ux
  - regulatory
former-id: HW-6RDR0X
parent: REQ-NY1FP1Y
order: a0
links:
  - type: refines
    target: REQ-NY1FP1Y
    confirmed: 58fbfc45ce54
---
The user account service shall encrypt user preferences using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly at least once per minute
- No error entries in the device log
