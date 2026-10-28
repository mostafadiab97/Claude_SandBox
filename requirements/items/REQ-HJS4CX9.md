---
id: REQ-HJS4CX9
type: system-requirement
title: Backlight restores safety limits
status: Review
priority: Medium
owner: Y. Saber
tags:
  - i18n
  - EMC
former-id: SYS-N54KFA
parent: REQ-2ZA2TRZ
order: b1Z
links:
  - type: refines
    target: REQ-WQB5JT6
    confirmed: a3e83ac40678
  - type: mitigates
    target: REQ-19NM7SG
    confirmed: 071ef93a7be9
---
The backlight shall calibrate error conditions at least once per minute.

**Rationale:** User preferences must stay consistent for the user in under 3 s.
