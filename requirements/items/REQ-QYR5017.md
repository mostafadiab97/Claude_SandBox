---
id: REQ-QYR5017
type: system-requirement
title: OTA server stores audit records
status: Approved
priority: Medium
owner: L. Samir
tags:
  - performance
former-id: SYS-5FQKC3
parent: REQ-RE9ZKHF
order: b0E
links:
  - type: refines
    target: REQ-BY89KNK
    confirmed: ae0f58e089a1
---
The OTA server shall log the set point for up to 8 zones.

**Rationale:** Firmware images must stay consistent for the user within 200 ms.
