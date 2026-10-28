---
id: SYS-Q6G2TQ
type: system-requirement
title: Boiler interface restores sensor readings
status: Draft
priority: Medium
parent: INFO-6DQTKV
order: 1430
links:
  - type: refines
    target: STK-W1SAZ0
    confirmed: f0954f8ba0a2
  - type: mitigates
    target: RSK-AA3YJ3
    confirmed: 84e686f1bbcc
---
The boiler interface shall report energy consumption within 200 ms.

**Rationale:** Firmware images must stay consistent for the user in under 3 s.
