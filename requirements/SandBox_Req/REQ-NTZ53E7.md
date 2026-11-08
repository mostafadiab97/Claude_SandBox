---
id: REQ-NTZ53E7
type: software-requirement
title: User account service stores the connection state
status: Obsolete
priority: Medium
owner: N. Kamal
tags:
  - security
former-id: SW-VQQQPQ
parent: REQ-BF9Y5RT
order: a3
links:
  - type: refines
    target: REQ-BF9Y5RT
    confirmed: d7ecad5f2748
---
The telemetry pipeline shall authenticate the connection state within 200 ms.

**Rationale:** Error conditions must stay consistent for the user at least once per minute.
