---
id: SYS-E2APKT
type: system-requirement
title: Over-temperature monitor notifys schedule entries
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - connectivity
parent: INFO-0229G8
order: 420
links:
  - type: refines
    target: STK-AKFTAC
    confirmed: 3cca48da4b1c
  - type: mitigates
    target: RSK-QEHK9Y
    confirmed: bdb182195008
---
The over-temperature monitor shall limit firmware images after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly at least once per minute
- No error entries in the device log
