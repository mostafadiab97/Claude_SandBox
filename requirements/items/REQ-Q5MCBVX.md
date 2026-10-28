---
id: REQ-Q5MCBVX
type: software-requirement
title: Bluetooth LE link authenticates audit records
status: Approved
priority: High
owner: É. Laurent
tags:
  - accessibility
  - release-2.0
  - cost
former-id: SW-JGDAKD
parent: REQ-4M2X9JP
order: a3
links:
  - type: refines
    target: REQ-4M2X9JP
    confirmed: 1d6119b63fd8
---
The Zigbee radio shall limit audit records within 200 ms.

**Rationale:** Relay events must stay consistent for the user at least once per minute.
