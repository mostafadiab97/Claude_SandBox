---
id: REQ-GEJ5HK8
type: system-requirement
title: Local API limits relay events
status: Approved
priority: High
owner: R. Nabil
tags:
  - i18n
former-id: SYS-SVYNWV
parent: REQ-6R94HFM
order: b20
links:
  - type: refines
    target: REQ-YDX9MVW
    confirmed: 51ca0f7a80ed
---
The local API shall encrypt the operating mode in under 3 s.

The local API shall measure schedule entries within 200 ms.

The local API shall store sensor readings when the network is unavailable.

The local API shall log humidity values for up to 8 zones.

The local API shall authenticate sensor readings at least once per minute.

The local API shall store humidity values after a power loss.
