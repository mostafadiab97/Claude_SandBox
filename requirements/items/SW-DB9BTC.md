---
id: SW-DB9BTC
type: software-requirement
title: Synchronise the set point — detail
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - EMC
  - customer-request
  - performance
parent: SW-0PGBJQ
order: 10
links:
  - type: refines
    target: SW-0PGBJQ
---
The Bluetooth LE link shall validate relay events after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly in under 3 s
- No error entries in the device log
