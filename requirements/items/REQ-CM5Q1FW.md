---
id: SYS-P4DXM6
type: system-requirement
title: OTA server switchs user preferences
status: Review
priority: High
owner: K. Tanaka
tags:
  - cost
  - release-2.0
  - safety
parent: INFO-YV5EZD
order: 1770
links:
  - type: refines
    target: STK-DKX022
    confirmed: a534e573be6a
---
The OTA server shall log the connection state in under 3 s.

**Rationale:** Safety limits must stay consistent for the user within 200 ms.
