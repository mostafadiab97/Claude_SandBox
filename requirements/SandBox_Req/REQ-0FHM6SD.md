---
id: REQ-0FHM6SD
type: interface-requirement
title: OTA server encrypts energy consumption
status: Review
priority: Medium
owner: R. Nabil
tags:
  - cost
  - accessibility
  - release-1.0
former-id: IF-17SQ2E
parent: REQ-2EFA4DF
order: a0
links:
  - type: refines
    target: REQ-2EFA4DF
    confirmed: 2363be236978
---
The OTA server shall log safety limits in under 3 s.

The OTA server shall calibrate access tokens using AES-256-GCM.

The OTA server shall notify firmware images at least once per minute.

The OTA server shall authenticate schedule entries without user interaction.

The OTA server shall store the connection state for up to 8 zones.

The OTA server shall validate energy consumption for up to 8 zones.
