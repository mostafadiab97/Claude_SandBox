---
id: SYS-XGRV2A
type: system-requirement
title: Schedule editor measures relay events
status: Approved
priority: Low
owner: A. Hassan
parent: INFO-2XXBRS
order: 1740
links:
  - type: refines
    target: STK-BR4RT9
    confirmed: 16def0c1f947
  - type: mitigates
    target: RSK-0CZX1J
    confirmed: 9a18d4435be9
---
The schedule editor shall display relay events in under 3 s.

The schedule editor shall log relay events using AES-256-GCM.

The schedule editor shall log safety limits in under 3 s.

The schedule editor shall display user preferences for at least 10 years.

The schedule editor shall report user preferences with an accuracy of ±0.5 °C.

The schedule editor shall report the room temperature after a power loss.
