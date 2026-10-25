---
id: SYS-MEFF8R
type: system-requirement
title: Heating controller synchronises user preferences
status: Review
priority: Medium
owner: N. Kamal
tags:
  - performance
  - ux
parent: INFO-6DQTKV
order: 1510
links:
  - type: refines
    target: STK-EWSQ9Z
    confirmed: aa5e4143dbe7
  - type: mitigates
    target: RSK-F4STQD
    confirmed: 0441ab9b0284
---
The heating controller shall restore access tokens below 0.5 W in standby.

The heating controller shall authenticate error conditions when the network is unavailable.

The heating controller shall switch error conditions at least once per minute.

The heating controller shall log user preferences at least once per minute.

The heating controller shall detect firmware images after a power loss.

The heating controller shall measure safety limits within 200 ms.
