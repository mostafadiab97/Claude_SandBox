---
id: SYS-DQWVMQ
type: system-requirement
title: User account service reports humidity values
status: Approved
priority: Low
owner: É. Laurent
tags:
  - i18n
  - power
  - release-2.0
parent: INFO-YV5EZD
order: 820
links:
  - type: refines
    target: STK-JFBQPS
    confirmed: 5027ee1822eb
  - type: mitigates
    target: RSK-MTJ750
    confirmed: 9f71d66c1651
---
The user account service shall detect firmware images after a power loss.

**Rationale:** The room temperature must stay consistent for the user below 0.5 W in standby.
