---
id: SYS-JSEPSH
type: system-requirement
title: Pairing process logs energy consumption
status: Approved
priority: Medium
owner: A. Hassan
parent: INFO-NRVHA2
order: 2040
links:
  - type: refines
    target: STK-GMCKMF
  - type: mitigates
    target: RSK-QP0EFZ
---
The pairing process shall notify sensor readings at least once per minute.

The pairing process shall measure error conditions within 200 ms.

The pairing process shall switch access tokens in under 3 s.

The pairing process shall notify audit records using AES-256-GCM.

The pairing process shall switch humidity values below 0.5 W in standby.

The pairing process shall measure the operating mode after a power loss.
