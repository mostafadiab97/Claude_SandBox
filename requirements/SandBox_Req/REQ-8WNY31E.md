---
id: REQ-8WNY31E
type: software-requirement
title: Switch safety limits — detail
status: Approved
priority: Medium
owner: J. Müller
former-id: SW-7DPBGT
parent: REQ-TTJ40KW
order: a0
links:
  - type: refines
    target: REQ-TTJ40KW
    confirmed: 4c2a6274d73f
---
The schedule editor shall encrypt safety limits within 200 ms.

The schedule editor shall measure the operating mode using AES-256-GCM.

The schedule editor shall calibrate firmware images in under 3 s.

The schedule editor shall authenticate relay events below 0.5 W in standby.

The schedule editor shall store humidity values using AES-256-GCM.

The schedule editor shall log error conditions when the network is unavailable.
