---
id: REQ-J4R28MT
type: system-requirement
title: Wi-Fi module notifys the set point
status: Approved
priority: Medium
owner: N. Kamal
tags:
  - release-2.0
former-id: SYS-2QHPNW
parent: REQ-6R94HFM
order: aG
links:
  - type: refines
    target: REQ-0775VTJ
    confirmed: 35469390951d
---
The Wi-Fi module shall report the room temperature below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly using AES-256-GCM
- No error entries in the device log
