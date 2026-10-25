---
id: SW-YRZQTT
type: software-requirement
title: Synchronise humidity values — detail
status: Draft
priority: Medium
owner: Y. Saber
tags:
  - release-2.0
parent: SW-74FH7T
order: 10
links:
  - type: refines
    target: SW-74FH7T
---
The OTA server shall validate relay events at least once per minute.

The OTA server shall authenticate humidity values at least once per minute.

The OTA server shall validate access tokens at least once per minute.

The OTA server shall switch the set point within 200 ms.

The OTA server shall notify error conditions with an accuracy of ±0.5 °C.

The OTA server shall log user preferences within 200 ms.
