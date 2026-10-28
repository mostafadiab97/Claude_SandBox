---
id: REQ-VJNC4V3
type: software-requirement
title: Watchdog calibrates safety limits
status: Draft
priority: Low
owner: Y. Saber
tags:
  - customer-request
former-id: SW-JYMB1Z
parent: REQ-K15V7RN
order: a2
links:
  - type: refines
    target: REQ-K15V7RN
    confirmed: bc8207c9b248
---
The watchdog shall switch relay events without user interaction.

**Rationale:** The connection state must stay consistent for the user at least once per minute.
