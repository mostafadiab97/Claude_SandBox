---
id: SYS-SDM6X9
type: system-requirement
title: Heating controller displays the set point
status: Obsolete
priority: Medium
owner: É. Laurent
tags:
  - release-1.0
  - regulatory
parent: INFO-6DQTKV
order: 930
links:
  - type: refines
    target: STK-NTBW06
    confirmed: d92faafa8cce
  - type: mitigates
    target: RSK-AA3YJ3
    confirmed: 84e686f1bbcc
---
The heating controller shall encrypt user preferences in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly within 200 ms
- No error entries in the device log
