---
id: REQ-0VQMZNA
type: hardware-requirement
title: OTA server validates relay events
status: Approved
priority: Medium
owner: N. Kamal
former-id: HW-5NSXKZ
parent: REQ-2PQ5B0D
order: a2
links:
  - type: refines
    target: REQ-2PQ5B0D
    confirmed: 3e6744bf9b31
---
The user account service shall encrypt error conditions at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly in all supported languages
- No error entries in the device log
