---
id: REQ-9K3P4DN
type: software-requirement
title: Watchdog encrypts the room temperature
status: Approved
priority: Medium
owner: K. Tanaka
former-id: SW-KPBX9A
parent: REQ-CYVT06S
order: a0
links:
  - type: refines
    target: REQ-CYVT06S
    confirmed: "735188e33202"
---
The secure boot shall switch relay events in under 3 s.

**Rationale:** Error conditions must stay consistent for the user at least once per minute.
