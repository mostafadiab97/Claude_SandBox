---
id: REQ-QG1H972
type: system-requirement
title: Bluetooth LE link reports the set point
status: Draft
priority: Medium
owner: K. Tanaka
tags:
  - customer-request
  - release-2.0
former-id: SYS-Q1RCFN
parent: REQ-6R94HFM
order: as
links:
  - type: refines
    target: REQ-7JDZJ5E
    confirmed: bd8a3050a12b
---
The Bluetooth LE link shall detect the set point within 200 ms.

**Rationale:** The set point must stay consistent for the user when the network is unavailable.
