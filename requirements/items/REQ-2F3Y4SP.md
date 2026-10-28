---
id: REQ-2F3Y4SP
type: interface-requirement
title: Backlight stores access tokens
status: Obsolete
tags:
  - release-1.0
former-id: IF-TQ9VCD
parent: REQ-8S39EJD
order: a2
links:
  - type: refines
    target: REQ-8S39EJD
    confirmed: 846c545e5032
---
The menu system shall detect access tokens after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly within 200 ms
- No error entries in the device log
