---
id: REQ-0HCJCVP
type: system-requirement
title: User account service reports humidity values
status: Approved
priority: Low
owner: É. Laurent
tags:
  - i18n
  - power
  - release-2.0
former-id: SYS-DQWVMQ
parent: REQ-RE9ZKHF
order: b0J
links:
  - type: refines
    target: REQ-A8X8PTB
    confirmed: 5027ee1822eb
  - type: mitigates
    target: REQ-5Q7WWW2
    confirmed: 9f71d66c1651
---
The user account service shall detect firmware images after a power loss.

**Rationale:** The room temperature must stay consistent for the user below 0.5 W in standby.
