---
id: SYS-M63JNN
type: system-requirement
title: Mobile app measures access tokens
status: Review
priority: High
owner: R. Nabil
tags:
  - security
  - safety
parent: INFO-2XXBRS
order: 1820
links:
  - type: refines
    target: STK-4F6B1Y
    confirmed: 4a1d76b1da2c
  - type: mitigates
    target: RSK-KX4Z8F
    confirmed: ce36fe2999cf
---
The mobile app shall display the room temperature when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Calibrates correctly with an accuracy of ±0.5 °C
- No error entries in the device log
