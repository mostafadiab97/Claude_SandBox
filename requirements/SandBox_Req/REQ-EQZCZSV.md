---
id: REQ-EQZCZSV
type: system-requirement
title: Zigbee radio reports sensor readings
status: Approved
priority: High
owner: Y. Saber
tags:
  - ux
  - regulatory
  - EMC
former-id: SYS-1KYW4V
parent: REQ-6R94HFM
order: b0g
links:
  - type: refines
    target: REQ-M9DYEF5
    confirmed: 44fc7956dbf8
---
The Zigbee radio shall synchronise schedule entries at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly in all supported languages
- No error entries in the device log
