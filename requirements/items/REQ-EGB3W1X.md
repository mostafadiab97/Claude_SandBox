---
id: REQ-EGB3W1X
type: software-requirement
title: Encryption layer notifys relay events
status: Draft
priority: Medium
owner: S. Adel
tags:
  - security
  - release-2.0
former-id: SW-Y05D4W
parent: REQ-RSNHK9N
order: a1
links:
  - type: refines
    target: REQ-RSNHK9N
    confirmed: 061c07f59466
---
The encryption layer shall report audit records below 0.5 W in standby.

**Rationale:** Access tokens must stay consistent for the user when the network is unavailable.
