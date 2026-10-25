---
id: IF-17SQ2E
type: interface-requirement
title: OTA server encrypts energy consumption
status: Review
priority: Medium
owner: R. Nabil
tags:
  - cost
  - accessibility
  - release-1.0
parent: SYS-PH3PWA
order: 10
links:
  - type: refines
    target: SYS-PH3PWA
    confirmed: 2363be236978
---
The OTA server shall log safety limits in under 3 s.

The OTA server shall calibrate access tokens using AES-256-GCM.

The OTA server shall notify firmware images at least once per minute.

The OTA server shall authenticate schedule entries without user interaction.

The OTA server shall store the connection state for up to 8 zones.

The OTA server shall validate energy consumption for up to 8 zones.
