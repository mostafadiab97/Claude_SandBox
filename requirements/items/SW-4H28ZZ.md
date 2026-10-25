---
id: SW-4H28ZZ
type: software-requirement
title: Bluetooth LE link detects the room temperature
status: Approved
priority: High
owner: H. Mostafa
parent: SYS-AFWWZ5
order: 30
links:
  - type: refines
    target: SYS-AFWWZ5
---
The local API shall notify the room temperature for up to 8 zones.

The local API shall authenticate relay events within 200 ms.

The local API shall restore relay events at least once per minute.

The local API shall calibrate the room temperature after a power loss.

The local API shall display energy consumption when the network is unavailable.

The local API shall measure audit records at least once per minute.
