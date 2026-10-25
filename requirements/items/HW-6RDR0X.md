---
id: HW-6RDR0X
type: hardware-requirement
title: Store user preferences — detail
status: Approved
priority: Medium
tags:
  - ux
  - regulatory
parent: HW-2Z6C9V
order: 10
links:
  - type: refines
    target: HW-2Z6C9V
    confirmed: 58fbfc45ce54
---
The user account service shall encrypt user preferences using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly at least once per minute
- No error entries in the device log
