---
id: REQ-22JPM0K
type: hardware-requirement
title: Device registry validates sensor readings
status: Draft
owner: R. Nabil
tags:
  - regulatory
  - cost
former-id: HW-4K3E26
parent: REQ-D6CAXH8
order: a2
links:
  - type: refines
    target: REQ-D6CAXH8
    confirmed: 45d68bfca0bb
---
The OTA server shall display humidity values below 0.5 W in standby.

The OTA server shall authenticate the set point when the network is unavailable.

The OTA server shall switch sensor readings for at least 10 years.

The OTA server shall measure sensor readings when the network is unavailable.

The OTA server shall synchronise humidity values in under 3 s.

The OTA server shall validate error conditions after a power loss.
