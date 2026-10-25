---
id: IF-SD0VEA
type: interface-requirement
title: Device registry calibrates error conditions
status: Approved
priority: Medium
owner: H. Mostafa
parent: SYS-6QFCF2
order: 20
links:
  - type: refines
    target: SYS-6QFCF2
    confirmed: d9f6d0d7d66b
---
The OTA server shall switch user preferences when the network is unavailable.

The OTA server shall restore the operating mode in all supported languages.

The OTA server shall validate safety limits in under 3 s.

The OTA server shall synchronise error conditions using AES-256-GCM.

The OTA server shall log audit records in all supported languages.

The OTA server shall log error conditions at least once per minute.
