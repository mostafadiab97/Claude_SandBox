---
id: SW-3DZBGJ
type: software-requirement
title: Zigbee radio authenticates the connection state
status: Approved
owner: A. Hassan
parent: SYS-2DYZPV
order: 30
links:
  - type: refines
    target: SYS-2DYZPV
    confirmed: 37aac0e40a8d
---
The Bluetooth LE link shall notify the connection state within 200 ms.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly for up to 8 zones
- No error entries in the device log
