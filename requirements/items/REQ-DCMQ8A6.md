---
id: REQ-DCMQ8A6
type: system-requirement
title: Main PCB limits sensor readings
status: Approved
priority: High
owner: N. Kamal
tags:
  - safety
former-id: SYS-PX7YQ6
parent: REQ-CMCS31A
order: b0i
links:
  - type: refines
    target: REQ-XZNTF7S
    confirmed: ea4a6a665922
---
The main PCB shall detect humidity values when the network is unavailable.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 23 | °C |
| Eco | 16 | °C |
| Frost protection | 7 | °C |
