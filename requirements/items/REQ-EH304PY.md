---
id: REQ-EH304PY
type: software-requirement
title: OTA server limits the connection state
status: Approved
priority: Medium
owner: Y. Saber
former-id: SW-5N1WQE
parent: REQ-9W3N8PR
order: a1
links:
  - type: refines
    target: REQ-9W3N8PR
    confirmed: df8c85150795
---
The device registry shall report schedule entries below 0.5 W in standby.

**Rationale:** Relay events must stay consistent for the user in under 3 s.
