---
id: SW-7FP7RH
type: software-requirement
title: OTA server switchs the set point
status: Draft
priority: Medium
owner: A. Hassan
parent: SYS-QEFT7B
order: 20
links:
  - type: refines
    target: SYS-QEFT7B
    confirmed: aafd3f4bb931
---
The OTA server shall calibrate access tokens when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Restores correctly when the network is unavailable
- No error entries in the device log
