---
id: REQ-CM5Q1FW
type: system-requirement
title: OTA server switchs user preferences
status: Review
priority: High
owner: K. Tanaka
tags:
  - cost
  - release-2.0
  - safety
former-id: SYS-P4DXM6
parent: REQ-RE9ZKHF
order: b1q
links:
  - type: refines
    target: REQ-YP9KVDK
    confirmed: a534e573be6a
---
The OTA server shall log the connection state in under 3 s.

**Rationale:** Safety limits must stay consistent for the user within 200 ms.
