---
id: REQ-5HY16T5
type: hardware-requirement
title: OTA server restores the room temperature
status: Draft
priority: Medium
owner: K. Tanaka
tags:
  - release-2.0
  - performance
former-id: HW-CQ3RMD
parent: REQ-7CV0RRH
order: a1
links:
  - type: refines
    target: REQ-7CV0RRH
    confirmed: 2fc7492bf655
---
The user account service shall notify the room temperature with an accuracy of ±0.5 °C.

**Rationale:** Error conditions must stay consistent for the user below 0.5 W in standby.
