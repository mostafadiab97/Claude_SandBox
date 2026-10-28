---
id: REQ-NKFJ115
type: system-requirement
title: Bluetooth LE link logs safety limits
status: Review
priority: High
owner: J. Müller
tags:
  - accessibility
former-id: SYS-JWQ89P
parent: REQ-6R94HFM
order: b0k
links:
  - type: refines
    target: REQ-YDX9MVW
    confirmed: 51ca0f7a80ed
---
The Bluetooth LE link shall validate access tokens when the network is unavailable.

**Rationale:** Schedule entries must stay consistent for the user below 0.5 W in standby.
