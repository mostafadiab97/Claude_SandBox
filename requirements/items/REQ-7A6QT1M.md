---
id: SW-TSCFKE
type: software-requirement
title: OTA server limits the connection state
status: Draft
priority: Medium
owner: J. Müller
tags:
  - accessibility
parent: SYS-XQJCRE
order: 30
links:
  - type: refines
    target: SYS-XQJCRE
    confirmed: edcb243104e3
---
The OTA server shall display the connection state in all supported languages.

The OTA server shall log humidity values for up to 8 zones.

The OTA server shall log error conditions without user interaction.

The OTA server shall restore the set point using AES-256-GCM.

The OTA server shall validate humidity values below 0.5 W in standby.

The OTA server shall detect humidity values using AES-256-GCM.
