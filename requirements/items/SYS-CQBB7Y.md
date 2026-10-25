---
id: SYS-CQBB7Y
type: system-requirement
title: Heat pump driver stores the connection state
status: Approved
priority: High
owner: J. Müller
parent: INFO-6DQTKV
order: 390
links:
  - type: refines
    target: STK-AA05P4
---
The heat pump driver shall notify the operating mode at least once per minute.

**Rationale:** Error conditions must stay consistent for the user at least once per minute.
