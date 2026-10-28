---
id: REQ-59JYD5D
type: software-requirement
title: Cloud backend synchronises the connection state
status: Approved
owner: H. Mostafa
former-id: SW-T008C5
parent: REQ-VCPXGX6
order: a0
links:
  - type: refines
    target: REQ-VCPXGX6
    confirmed: aafd3f4bb931
---
The OTA server shall report relay events with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly below 0.5 W in standby
- No error entries in the device log
