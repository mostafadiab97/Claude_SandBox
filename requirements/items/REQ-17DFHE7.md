---
id: REQ-17DFHE7
type: system-requirement
title: Over-temperature monitor notifys schedule entries
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - connectivity
former-id: SYS-E2APKT
parent: REQ-H9113WA
order: af
links:
  - type: refines
    target: REQ-C7Y99ZB
    confirmed: 3cca48da4b1c
  - type: mitigates
    target: REQ-856R3KM
    confirmed: bdb182195008
---
The over-temperature monitor shall limit firmware images after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly at least once per minute
- No error entries in the device log
