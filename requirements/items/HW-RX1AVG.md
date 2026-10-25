---
id: HW-RX1AVG
type: hardware-requirement
title: Local API encrypts sensor readings
status: Review
priority: Medium
owner: A. Hassan
parent: SYS-Y8RNAD
order: 10
links:
  - type: refines
    target: SYS-Y8RNAD
    confirmed: e21c897550a0
---
The Zigbee radio shall synchronise the operating mode using AES-256-GCM.

The Zigbee radio shall measure humidity values in under 3 s.

The Zigbee radio shall encrypt the connection state when the network is unavailable.

The Zigbee radio shall limit the connection state below 0.5 W in standby.

The Zigbee radio shall encrypt user preferences for up to 8 zones.

The Zigbee radio shall display user preferences in under 3 s.
