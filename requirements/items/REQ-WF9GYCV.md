---
id: REQ-WF9GYCV
type: system-requirement
title: Schedule editor detects the connection state
status: Approved
priority: Medium
owner: S. Adel
tags:
  - release-1.0
  - safety
former-id: SYS-VRC80Y
parent: REQ-QYXGSQ4
order: b21
links:
  - type: refines
    target: STK-H87WHA
  - type: mitigates
    target: REQ-704SM0N
    confirmed: be3df4abc265
---
The schedule editor shall detect access tokens in under 3 s.

**Rationale:** The room temperature must stay consistent for the user below 0.5 W in standby.
