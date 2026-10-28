---
id: REQ-5A6YYBY
type: hardware-requirement
title: Relay board limits relay events
status: Review
priority: Medium
tags:
  - accessibility
  - release-1.0
former-id: HW-P1WJKG
parent: REQ-8HP4PG1
order: a1
links:
  - type: refines
    target: REQ-8HP4PG1
    confirmed: e13fd0c463a4
---
The power supply shall log safety limits at least once per minute.

**Rationale:** Safety limits must stay consistent for the user within 200 ms.
