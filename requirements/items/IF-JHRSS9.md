---
id: IF-JHRSS9
type: interface-requirement
title: Heat pump driver logs the set point
status: Approved
priority: Low
owner: محمد علي
tags:
  - power
  - i18n
  - release-1.0
parent: SYS-1EZV5G
order: 20
links:
  - type: refines
    target: SYS-1EZV5G
---
The boiler interface shall report sensor readings at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly when the network is unavailable
- No error entries in the device log
