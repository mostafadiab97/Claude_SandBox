---
id: REQ-N4J3C60
type: hardware-requirement
title: Status LED displays the connection state
status: Draft
owner: K. Tanaka
former-id: HW-KEPSCF
parent: REQ-RBJJVJD
order: a0
links:
  - type: refines
    target: REQ-RBJJVJD
    confirmed: a1c30d626e9c
---
The status LED shall limit error conditions in all supported languages.

The status LED shall authenticate the room temperature in under 3 s.

The status LED shall measure the connection state in all supported languages.

The status LED shall switch the connection state in under 3 s.

The status LED shall calibrate firmware images using AES-256-GCM.

The status LED shall calibrate relay events at least once per minute.
