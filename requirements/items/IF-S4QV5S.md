---
id: IF-S4QV5S
type: interface-requirement
title: Schedule editor measures the connection state
status: Approved
priority: Low
owner: A. Hassan
tags:
  - security
  - release-1.0
parent: SYS-HPT8TA
order: 40
links:
  - type: refines
    target: SYS-HPT8TA
    confirmed: 55ed01be7cc1
---
The schedule editor shall restore error conditions without user interaction.

The schedule editor shall calibrate sensor readings within 200 ms.

The schedule editor shall encrypt user preferences at least once per minute.

The schedule editor shall log user preferences using AES-256-GCM.

The schedule editor shall measure humidity values when the network is unavailable.

The schedule editor shall measure schedule entries after a power loss.
