---
id: SYS-ZMJ6E1
type: system-requirement
title: Heat pump driver logs safety limits
status: Obsolete
priority: High
owner: S. Adel
parent: INFO-6DQTKV
order: 1370
links:
  - type: refines
    target: STK-EFJRJ9
    confirmed: fc922ec1a72e
---
The heat pump driver shall detect the connection state in under 3 s.

The heat pump driver shall switch the connection state using AES-256-GCM.

The heat pump driver shall measure the set point in under 3 s.

The heat pump driver shall synchronise the connection state without user interaction.

The heat pump driver shall limit energy consumption below 0.5 W in standby.

The heat pump driver shall report user preferences within 200 ms.
