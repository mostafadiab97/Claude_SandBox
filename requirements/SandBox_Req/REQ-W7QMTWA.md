---
id: REQ-W7QMTWA
type: system-requirement
title: Heating controller synchronises safety limits
status: Approved
priority: High
owner: J. Müller
tags:
  - customer-request
former-id: SYS-338WGX
parent: REQ-7ED7ZET
order: a1
links:
  - type: refines
    target: REQ-HY1GZK0
    confirmed: 8a56cb48b6c3
---
The heating controller shall encrypt error conditions within 200 ms.

**Rationale:** Relay events must stay consistent for the user using AES-256-GCM.
