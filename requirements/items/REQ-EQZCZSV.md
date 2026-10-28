---
id: SYS-1KYW4V
type: system-requirement
title: Zigbee radio reports sensor readings
status: Approved
priority: High
owner: Y. Saber
tags:
  - ux
  - regulatory
  - EMC
parent: INFO-NRVHA2
order: 1050
links:
  - type: refines
    target: STK-AAZ4HV
    confirmed: 44fc7956dbf8
---
The Zigbee radio shall synchronise schedule entries at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly in all supported languages
- No error entries in the device log
