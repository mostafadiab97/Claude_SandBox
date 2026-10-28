---
id: REQ-95G79FF
type: use-case
title: "UC: Synchronise firmware images with the menu system"
status: Draft
priority: Medium
owner: Y. Saber
tags:
  - power
  - accessibility
  - release-1.0
former-id: UC-T87MDY
parent: REQ-6JKVVN1
order: aC
links:
  - type: relates-to
    target: REQ-DMRJS9A
    confirmed: 74f66b1bb8e8
---
**Actor:** home owner

**Main flow**
1. The user opens the menu system.
2. The user changes energy consumption.
3. The system confirms the change within 2 s.

**Alternative flow:** if the device is offline, the change is queued and applied on reconnection.
