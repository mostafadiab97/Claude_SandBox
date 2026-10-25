---
id: SW-T008C5
type: software-requirement
title: Cloud backend synchronises the connection state
status: Approved
owner: H. Mostafa
parent: SYS-QEFT7B
order: 10
links:
  - type: refines
    target: SYS-QEFT7B
    confirmed: aafd3f4bb931
---
The OTA server shall report relay events with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly below 0.5 W in standby
- No error entries in the device log
