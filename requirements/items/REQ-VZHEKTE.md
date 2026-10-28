---
id: REQ-VZHEKTE
type: software-requirement
title: Synchronise humidity values — detail
status: Draft
priority: Medium
owner: Y. Saber
tags:
  - release-2.0
former-id: SW-YRZQTT
parent: REQ-AAE8RAX
order: a0
links:
  - type: refines
    target: REQ-AAE8RAX
    confirmed: 89ab6af8e498
---
The OTA server shall validate relay events at least once per minute.

The OTA server shall authenticate humidity values at least once per minute.

The OTA server shall validate access tokens at least once per minute.

The OTA server shall switch the set point within 200 ms.

The OTA server shall notify error conditions with an accuracy of ±0.5 °C.

The OTA server shall log user preferences within 200 ms.
