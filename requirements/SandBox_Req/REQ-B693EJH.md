---
id: REQ-B693EJH
type: software-requirement
title: Detect the operating mode — detail
status: Draft
priority: Medium
owner: Y. Saber
former-id: SW-Z7GCYM
parent: REQ-00G3MSF
order: a0
links:
  - type: refines
    target: REQ-00G3MSF
    confirmed: 1c6a633bcb0f
---
The Zigbee radio shall detect the connection state when the network is unavailable.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly after a power loss
- No error entries in the device log
