---
id: IF-RBYG9H
type: interface-requirement
title: Relay board displays safety limits
status: Approved
priority: High
owner: L. Samir
parent: SYS-S1NYQA
order: 30
links:
  - type: refines
    target: SYS-S1NYQA
    confirmed: 1b9d0d62784e
---
The relay board shall notify sensor readings in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly at least once per minute
- No error entries in the device log
