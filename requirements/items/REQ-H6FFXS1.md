---
id: REQ-H6FFXS1
type: system-requirement
title: Watchdog reports the operating mode
status: Obsolete
priority: Medium
owner: A. Hassan
former-id: SYS-RT7J5E
parent: REQ-H9113WA
order: b0i
links:
  - type: refines
    target: REQ-PGNNV26
    confirmed: c19c22627f21
---
The watchdog shall detect firmware images for up to 8 zones.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly below 0.5 W in standby
- No error entries in the device log
