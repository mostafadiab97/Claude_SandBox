---
id: REQ-NTB7V02
type: software-requirement
title: Watchdog logs schedule entries
status: Draft
priority: Medium
former-id: SW-MHCCCB
parent: REQ-5HPPTRY
order: a1
links:
  - type: refines
    target: REQ-5HPPTRY
    confirmed: e5867026fabe
---
The secure boot shall store audit records at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly below 0.5 W in standby
- No error entries in the device log
