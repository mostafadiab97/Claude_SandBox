---
id: REQ-T8DHZP1
type: interface-requirement
title: Schedule editor measures the connection state
status: Approved
priority: Low
owner: A. Hassan
tags:
  - security
  - release-1.0
former-id: IF-S4QV5S
parent: REQ-JYNEA7Y
order: a3
links:
  - type: refines
    target: REQ-JYNEA7Y
    confirmed: 55ed01be7cc1
---
The schedule editor shall restore error conditions without user interaction.

The schedule editor shall calibrate sensor readings within 200 ms.

The schedule editor shall encrypt user preferences at least once per minute.

The schedule editor shall log user preferences using AES-256-GCM.

The schedule editor shall measure humidity values when the network is unavailable.

The schedule editor shall measure schedule entries after a power loss.
