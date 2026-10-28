---
id: REQ-03C26AS
type: interface-requirement
title: Device registry calibrates error conditions
status: Approved
priority: Medium
owner: H. Mostafa
former-id: IF-SD0VEA
parent: REQ-3P9VR9B
order: a1
links:
  - type: refines
    target: REQ-3P9VR9B
    confirmed: d9f6d0d7d66b
---
The OTA server shall switch user preferences when the network is unavailable.

The OTA server shall restore the operating mode in all supported languages.

The OTA server shall validate safety limits in under 3 s.

The OTA server shall synchronise error conditions using AES-256-GCM.

The OTA server shall log audit records in all supported languages.

The OTA server shall log error conditions at least once per minute.
