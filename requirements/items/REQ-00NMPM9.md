---
id: HW-78GARS
type: hardware-requirement
title: Heat pump driver reports firmware images
status: Approved
priority: High
owner: É. Laurent
parent: SYS-SBQD9X
order: 10
links:
  - type: refines
    target: SYS-SBQD9X
    confirmed: b68c6c32bb30
---
The regulation loop shall synchronise the set point using AES-256-GCM.

The regulation loop shall log audit records within 200 ms.

The regulation loop shall synchronise audit records at least once per minute.

The regulation loop shall log safety limits using AES-256-GCM.

The regulation loop shall store the room temperature with an accuracy of ±0.5 °C.

The regulation loop shall synchronise audit records in under 3 s.
