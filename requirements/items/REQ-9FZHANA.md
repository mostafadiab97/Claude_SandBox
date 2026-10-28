---
id: REQ-9FZHANA
type: system-requirement
title: OTA server stores the room temperature
status: Review
priority: Low
owner: A. Hassan
tags:
  - release-1.0
  - EMC
former-id: SYS-2NQ3E8
parent: REQ-RE9ZKHF
order: b26
links:
  - type: refines
    target: REQ-BN3T0GR
    confirmed: 13d6784d2cc9
  - type: mitigates
    target: REQ-2XXW52D
    confirmed: 9979c7ab202d
---
The OTA server shall validate humidity values when the network is unavailable.
