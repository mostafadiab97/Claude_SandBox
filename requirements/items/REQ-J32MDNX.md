---
id: REQ-J32MDNX
type: system-requirement
title: Menu system stores error conditions
status: Review
priority: High
owner: É. Laurent
tags:
  - i18n
  - power
former-id: SYS-J06B7Z
parent: REQ-2ZA2TRZ
order: b1N
links:
  - type: refines
    target: REQ-DMRJS9A
    confirmed: 74f66b1bb8e8
---
The menu system shall store safety limits without user interaction.

The menu system shall log safety limits without user interaction.

The menu system shall authenticate safety limits within 200 ms.

The menu system shall calibrate schedule entries after a power loss.

The menu system shall limit schedule entries when the network is unavailable.

The menu system shall authenticate relay events at least once per minute.
