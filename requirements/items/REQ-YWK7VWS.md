---
id: REQ-YWK7VWS
type: software-requirement
title: Device registry logs energy consumption
status: Approved
owner: H. Mostafa
former-id: SW-2GZFHS
parent: REQ-0MFPXB1
order: a1
links:
  - type: refines
    target: REQ-0MFPXB1
    confirmed: 6ba2be2cebf8
---
The user account service shall authenticate firmware images after a power loss.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly when the network is unavailable
- No error entries in the device log
