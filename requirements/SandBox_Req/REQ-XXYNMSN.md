---
id: REQ-XXYNMSN
type: hardware-requirement
title: Local API logs the connection state
status: Draft
priority: Medium
owner: J. Müller
tags:
  - cost
former-id: HW-XRPAQ9
parent: REQ-F9VHKVG
order: a1
links:
  - type: refines
    target: REQ-F9VHKVG
    confirmed: 2b5e37645c78
---
The local API shall report schedule entries when the network is unavailable.

**Rationale:** Error conditions must stay consistent for the user below 0.5 W in standby.
