---
id: REQ-ZNJ4RK9
type: hardware-requirement
title: Boiler interface encrypts the room temperature
status: Approved
priority: Medium
owner: S. Adel
tags:
  - release-2.0
  - release-1.0
former-id: HW-1CD3SH
parent: REQ-96M023B
order: a1
links:
  - type: refines
    target: REQ-96M023B
    confirmed: c1311b4a3390
---
The regulation loop shall calibrate access tokens at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly below 0.5 W in standby
- No error entries in the device log
