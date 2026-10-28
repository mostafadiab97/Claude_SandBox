---
id: REQ-00NMPM9
type: hardware-requirement
title: Heat pump driver reports firmware images
status: Approved
priority: High
owner: É. Laurent
former-id: HW-78GARS
parent: REQ-XYGBK0A
order: a0
links:
  - type: refines
    target: REQ-XYGBK0A
    confirmed: b68c6c32bb30
---
The regulation loop shall synchronise the set point using AES-256-GCM.

The regulation loop shall log audit records within 200 ms.

The regulation loop shall synchronise audit records at least once per minute.

The regulation loop shall log safety limits using AES-256-GCM.

The regulation loop shall store the room temperature with an accuracy of ±0.5 °C.

The regulation loop shall synchronise audit records in under 3 s.
