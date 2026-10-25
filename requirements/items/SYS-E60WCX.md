---
id: SYS-E60WCX
type: system-requirement
title: Device registry switchs the connection state
status: Approved
priority: High
owner: H. Mostafa
tags:
  - accessibility
  - release-1.0
parent: INFO-YV5EZD
order: 1970
links:
  - type: refines
    target: STK-VT1KVD
  - type: mitigates
    target: RSK-8PEBF8
---
The device registry shall display relay events using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Logs correctly within 200 ms
- No error entries in the device log
