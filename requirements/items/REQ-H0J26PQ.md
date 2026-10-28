---
id: REQ-H0J26PQ
type: system-requirement
title: Heat pump driver stores the connection state
status: Approved
priority: High
owner: J. Müller
former-id: SYS-CQBB7Y
parent: REQ-7ED7ZET
order: ac
links:
  - type: refines
    target: REQ-REA5VGA
    confirmed: e2bec3bcd11c
---
The heat pump driver shall notify the operating mode at least once per minute.

**Rationale:** Error conditions must stay consistent for the user at least once per minute.
