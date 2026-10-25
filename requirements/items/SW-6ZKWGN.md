---
id: SW-6ZKWGN
type: software-requirement
title: Watchdog restores audit records
status: Approved
priority: Medium
owner: É. Laurent
parent: SYS-KF7ZE3
order: 10
links:
  - type: refines
    target: SYS-KF7ZE3
---
The secure boot shall notify audit records when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly without user interaction
- No error entries in the device log
