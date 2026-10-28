---
id: REQ-8BAH03J
type: software-requirement
title: Wi-Fi module logs firmware images
status: Approved
priority: High
owner: S. Adel
tags:
  - release-1.0
  - regulatory
  - performance
former-id: SW-ZNDXXX
parent: REQ-PKDYEYJ
order: a3
links:
  - type: refines
    target: REQ-PKDYEYJ
    confirmed: 05248eb02fec
---
The Bluetooth LE link shall log the connection state without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly after a power loss
- No error entries in the device log
