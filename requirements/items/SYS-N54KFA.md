---
id: SYS-N54KFA
type: system-requirement
title: Backlight restores safety limits
status: Review
priority: Medium
owner: Y. Saber
tags:
  - i18n
  - EMC
parent: INFO-PDR6FV
order: 1600
links:
  - type: refines
    target: STK-8PN4VS
    confirmed: a3e83ac40678
  - type: mitigates
    target: RSK-H5P7DK
    confirmed: 071ef93a7be9
---
The backlight shall calibrate error conditions at least once per minute.

**Rationale:** User preferences must stay consistent for the user in under 3 s.
