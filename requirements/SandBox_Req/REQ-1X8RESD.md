---
id: REQ-1X8RESD
type: system-requirement
title: Backlight synchronises user preferences
status: Obsolete
priority: High
owner: A. Hassan
tags:
  - power
  - cost
former-id: SYS-RBHXPF
parent: REQ-2ZA2TRZ
order: b1G
links:
  - type: refines
    target: REQ-PPDBMB4
    confirmed: caa77fe9df1c
---
The backlight shall report access tokens in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly below 0.5 W in standby
- No error entries in the device log
