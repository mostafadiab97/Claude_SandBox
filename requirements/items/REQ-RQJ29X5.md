---
id: REQ-RQJ29X5
type: software-requirement
title: Watchdog restores audit records
status: Approved
priority: Medium
owner: É. Laurent
former-id: SW-6ZKWGN
parent: REQ-6PB57PX
order: a0
links:
  - type: refines
    target: REQ-6PB57PX
    confirmed: 3dd7a8ccfac1
---
The secure boot shall notify audit records when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly without user interaction
- No error entries in the device log
