---
id: REQ-CH1WNFD
type: software-requirement
title: Validate safety limits — detail
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - performance
former-id: SW-KX8D6R
parent: REQ-8CK0YD6
order: a0
links:
  - type: refines
    target: REQ-8CK0YD6
    confirmed: de8b2ae7c14f
---
The OTA server shall report access tokens in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly at least once per minute
- No error entries in the device log
