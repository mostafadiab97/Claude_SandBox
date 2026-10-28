---
id: SYS-ANP21Y
type: system-requirement
title: Cloud backend switchs sensor readings
status: Approved
priority: Medium
tags:
  - release-2.0
parent: INFO-YV5EZD
order: 1010
links:
  - type: refines
    target: STK-JFBQPS
    confirmed: 5027ee1822eb
---
The cloud backend shall detect energy consumption when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly using AES-256-GCM
- No error entries in the device log
