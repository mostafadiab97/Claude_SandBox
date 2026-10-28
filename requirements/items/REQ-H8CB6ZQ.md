---
id: REQ-H8CB6ZQ
type: system-requirement
title: Pairing process logs energy consumption
status: Approved
priority: Medium
owner: A. Hassan
former-id: SYS-JSEPSH
parent: REQ-6R94HFM
order: b2H
links:
  - type: refines
    target: REQ-5EJHVJ8
    confirmed: f47328374a2b
  - type: mitigates
    target: REQ-JX165DV
    confirmed: b4372c636b9e
---
The pairing process shall notify sensor readings at least once per minute.

The pairing process shall measure error conditions within 200 ms.

The pairing process shall switch access tokens in under 3 s.

The pairing process shall notify audit records using AES-256-GCM.

The pairing process shall switch humidity values below 0.5 W in standby.

The pairing process shall measure the operating mode after a power loss.
