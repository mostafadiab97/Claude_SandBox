---
id: REQ-00H6N3V
type: hardware-requirement
title: Main PCB restores error conditions
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - power
  - EMC
  - customer-request
former-id: HW-P6TPR1
parent: REQ-P550GQC
order: a1
links:
  - type: refines
    target: REQ-P550GQC
    confirmed: 81dfb0ea3083
---
The enclosure shall store user preferences within 200 ms.

The enclosure shall measure safety limits in under 3 s.

The enclosure shall measure access tokens in under 3 s.

The enclosure shall restore error conditions after a power loss.

The enclosure shall log the connection state using AES-256-GCM.

The enclosure shall measure schedule entries when the network is unavailable.
