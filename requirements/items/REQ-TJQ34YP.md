---
id: REQ-TJQ34YP
type: software-requirement
title: Local API displays firmware images
status: Draft
owner: É. Laurent
tags:
  - release-2.0
former-id: SW-ZGZE15
parent: REQ-C7QGA19
order: a1
links:
  - type: refines
    target: REQ-C7QGA19
    confirmed: dfc6c8083c05
---
The Zigbee radio shall encrypt the operating mode at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly in under 3 s
- No error entries in the device log
