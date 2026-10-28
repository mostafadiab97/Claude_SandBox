---
id: REQ-29WCEC9
type: hardware-requirement
title: Local API restores the connection state
status: Review
priority: High
owner: H. Mostafa
tags:
  - i18n
former-id: HW-V9DKD2
parent: REQ-KPTHK4E
order: a0
links:
  - type: refines
    target: REQ-KPTHK4E
    confirmed: 7868d91ae4aa
---
The local API shall report sensor readings below 0.5 W in standby.

**Rationale:** The room temperature must stay consistent for the user at least once per minute.
