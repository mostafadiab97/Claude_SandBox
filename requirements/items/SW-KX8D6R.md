---
id: SW-KX8D6R
type: software-requirement
title: Validate safety limits — detail
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - performance
parent: SW-2JXWJW
order: 10
links:
  - type: refines
    target: SW-2JXWJW
---
The OTA server shall report access tokens in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly at least once per minute
- No error entries in the device log
