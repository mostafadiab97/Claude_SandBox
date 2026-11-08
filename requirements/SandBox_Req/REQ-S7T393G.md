---
id: REQ-S7T393G
type: hardware-requirement
title: Main PCB displays audit records
status: Approved
priority: Medium
owner: R. Nabil
former-id: HW-KR83ET
parent: REQ-SQ5X7CQ
order: a3
links:
  - type: refines
    target: REQ-SQ5X7CQ
    confirmed: 85f6bb475fe2
---
The relay board shall calibrate audit records below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly within 200 ms
- No error entries in the device log
