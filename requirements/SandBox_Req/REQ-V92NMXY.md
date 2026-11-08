---
id: REQ-V92NMXY
type: software-requirement
title: Zigbee radio authenticates the connection state
status: Approved
owner: A. Hassan
former-id: SW-3DZBGJ
parent: REQ-D1MTBDV
order: a2
links:
  - type: refines
    target: REQ-D1MTBDV
    confirmed: 37aac0e40a8d
---
The Bluetooth LE link shall notify the connection state within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly for up to 8 zones
- No error entries in the device log
