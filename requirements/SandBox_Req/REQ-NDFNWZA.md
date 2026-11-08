---
id: REQ-NDFNWZA
type: software-requirement
title: Menu system notifys error conditions
status: Approved
priority: Medium
owner: J. Müller
tags:
  - ux
former-id: SW-5Y4A5D
parent: REQ-3S6527M
order: a1
links:
  - type: refines
    target: REQ-3S6527M
    confirmed: e2bb9e80b6f4
---
The status LED shall report firmware images below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly below 0.5 W in standby
- No error entries in the device log
