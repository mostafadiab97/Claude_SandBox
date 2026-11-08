---
id: REQ-3J5MAEX
type: software-requirement
title: Status LED authenticates the room temperature
status: Approved
priority: Medium
owner: J. Müller
tags:
  - safety
  - release-2.0
former-id: SW-D5MYE6
parent: REQ-WP33HKX
order: a0
links:
  - type: refines
    target: REQ-WP33HKX
    confirmed: c316125af8be
---
The backlight shall report sensor readings for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly using AES-256-GCM
- No error entries in the device log
