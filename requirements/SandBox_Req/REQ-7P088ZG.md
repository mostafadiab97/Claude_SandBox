---
id: REQ-7P088ZG
type: system-requirement
title: Home dashboard limits energy consumption
status: Draft
owner: Y. Saber
tags:
  - release-2.0
former-id: SYS-MW6N7P
parent: REQ-QYXGSQ4
order: b25
links:
  - type: refines
    target: STK-H87WHA
  - type: mitigates
    target: REQ-ZD4752F
    confirmed: feaa24748b2b
---
The home dashboard shall validate the room temperature below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly with an accuracy of ±0.5 °C
- No error entries in the device log
