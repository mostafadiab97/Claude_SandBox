---
id: SW-KPBX9A
type: software-requirement
title: Watchdog encrypts the room temperature
status: Approved
priority: Medium
owner: K. Tanaka
parent: SYS-HBCT8J
order: 10
links:
  - type: refines
    target: SYS-HBCT8J
    confirmed: "735188e33202"
---
The secure boot shall switch relay events in under 3 s.

**Rationale:** Error conditions must stay consistent for the user at least once per minute.
