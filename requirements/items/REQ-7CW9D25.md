---
id: REQ-7CW9D25
type: hardware-requirement
title: Calibrate error conditions — detail
status: Review
priority: High
former-id: HW-RMTAMA
parent: REQ-QDK6128
order: a0
links:
  - type: refines
    target: REQ-QDK6128
    confirmed: 75ad818553c9
---
The Zigbee radio shall log the connection state with an accuracy of ±0.5 °C.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly when the network is unavailable
- No error entries in the device log
