---
id: REQ-9E375HR
type: system-requirement
title: Heat pump driver logs safety limits
status: Obsolete
priority: High
owner: S. Adel
former-id: SYS-ZMJ6E1
parent: REQ-7ED7ZET
order: b1C
links:
  - type: refines
    target: REQ-6WZCEAT
    confirmed: fc922ec1a72e
---
The heat pump driver shall detect the connection state in under 3 s.

The heat pump driver shall switch the connection state using AES-256-GCM.

The heat pump driver shall measure the set point in under 3 s.

The heat pump driver shall synchronise the connection state without user interaction.

The heat pump driver shall limit energy consumption below 0.5 W in standby.

The heat pump driver shall report user preferences within 200 ms.
