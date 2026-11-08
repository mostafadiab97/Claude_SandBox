---
id: REQ-0M1NS5Z
type: use-case
title: "UC: Synchronise firmware images with the backlight"
status: Draft
priority: Low
owner: محمد علي
former-id: UC-8MACDV
parent: REQ-6JKVVN1
order: aE
links:
  - type: relates-to
    target: REQ-PPDBMB4
    confirmed: caa77fe9df1c
---
**Actor:** home owner

**Main flow**
1. The user opens the backlight.
2. The user changes the set point.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.
