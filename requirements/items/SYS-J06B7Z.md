---
id: SYS-J06B7Z
type: system-requirement
title: Menu system stores error conditions
status: Review
priority: High
owner: É. Laurent
tags:
  - i18n
  - power
parent: INFO-PDR6FV
order: 1480
links:
  - type: refines
    target: STK-PCP268
    confirmed: 74f66b1bb8e8
---
The menu system shall store safety limits without user interaction.

The menu system shall log safety limits without user interaction.

The menu system shall authenticate safety limits within 200 ms.

The menu system shall calibrate schedule entries after a power loss.

The menu system shall limit schedule entries when the network is unavailable.

The menu system shall authenticate relay events at least once per minute.
