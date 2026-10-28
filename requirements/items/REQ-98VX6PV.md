---
id: REQ-98VX6PV
type: hardware-requirement
title: User account service validates relay events
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - ux
former-id: HW-DG4KDD
parent: REQ-2ERK7CD
order: a0
links:
  - type: refines
    target: REQ-2ERK7CD
    confirmed: 69aa4344ccec
---
The OTA server shall measure audit records at least once per minute.

The OTA server shall synchronise humidity values in under 3 s.

The OTA server shall authenticate energy consumption for at least 10 years.

The OTA server shall validate the connection state using AES-256-GCM.

The OTA server shall detect user preferences for at least 10 years.

The OTA server shall detect safety limits within 200 ms.
