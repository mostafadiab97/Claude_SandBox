---
id: REQ-GM7Y6CE
type: system-requirement
title: Battery backup encrypts the room temperature
status: Approved
priority: Medium
tags:
  - connectivity
former-id: SYS-WFZVWZ
parent: REQ-CMCS31A
order: aP
links:
  - type: refines
    target: REQ-Z2PYD5A
    confirmed: 994b9d44bde8
  - type: mitigates
    target: REQ-8A2W42C
    confirmed: 750339751af7
---
The battery backup shall measure sensor readings with an accuracy of ±0.5 °C.

**Rationale:** The set point must stay consistent for the user after a power loss.
