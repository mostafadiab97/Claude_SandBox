---
id: REQ-6JEC1MF
type: system-requirement
title: Enclosure stores the room temperature
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - power
  - release-2.0
  - release-1.0
former-id: SYS-AXK7J9
parent: REQ-CMCS31A
order: b2b
links:
  - type: refines
    target: REQ-V8PT5BV
    confirmed: b0af11a5c3c2
---
The enclosure shall authenticate schedule entries at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly when the network is unavailable
- No error entries in the device log
