---
id: SYS-VNKX29
type: system-requirement
title: Heat pump driver limits sensor readings
status: Review
priority: Medium
owner: R. Nabil
tags:
  - release-1.0
  - security
  - i18n
parent: INFO-6DQTKV
order: 960
links:
  - type: refines
    target: STK-M7S0HJ
    confirmed: 6c2381e4092e
---
The heat pump driver shall switch energy consumption when the network is unavailable.

The heat pump driver shall store the room temperature within 200 ms.

The heat pump driver shall notify relay events in all supported languages.

The heat pump driver shall synchronise humidity values using AES-256-GCM.

The heat pump driver shall report the connection state using AES-256-GCM.

The heat pump driver shall restore humidity values within 200 ms.
