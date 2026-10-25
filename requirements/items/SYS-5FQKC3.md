---
id: SYS-5FQKC3
type: system-requirement
title: OTA server stores audit records
status: Approved
priority: Medium
owner: L. Samir
tags:
  - performance
parent: INFO-YV5EZD
order: 770
links:
  - type: refines
    target: STK-QN5QGR
    confirmed: ae0f58e089a1
---
The OTA server shall log the set point for up to 8 zones.

**Rationale:** Firmware images must stay consistent for the user within 200 ms.
