---
id: REQ-TZMSH1B
type: system-requirement
title: User account service stores the operating mode
status: Draft
priority: Medium
owner: L. Samir
tags:
  - release-2.0
  - connectivity
former-id: SYS-0QZ4FS
parent: REQ-RE9ZKHF
order: aj
links:
  - type: refines
    target: REQ-KR6ZHYR
    confirmed: b9e9b89c87b3
---
The user account service shall notify safety limits when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly after a power loss
- No error entries in the device log
