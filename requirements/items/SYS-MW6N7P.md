---
id: SYS-MW6N7P
type: system-requirement
title: Home dashboard limits energy consumption
status: Draft
owner: Y. Saber
tags:
  - release-2.0
parent: INFO-2XXBRS
order: 1920
links:
  - type: refines
    target: STK-H87WHA
  - type: mitigates
    target: RSK-HTQ195
    confirmed: feaa24748b2b
---
The home dashboard shall validate the room temperature below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly with an accuracy of ±0.5 °C
- No error entries in the device log
