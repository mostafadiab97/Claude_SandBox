---
id: REQ-NPCDBRR
type: software-requirement
title: Over-temperature monitor switchs sensor readings
status: Review
priority: High
owner: L. Samir
tags:
  - safety
  - regulatory
former-id: SW-J1F7RJ
parent: REQ-5TMVTPD
order: a0
links:
  - type: refines
    target: REQ-5TMVTPD
    confirmed: 660a8488c508
---
The over-temperature monitor shall switch safety limits using AES-256-GCM.

The over-temperature monitor shall notify the room temperature when the network is unavailable.

The over-temperature monitor shall detect humidity values in under 3 s.

The over-temperature monitor shall authenticate humidity values for up to 8 zones.

The over-temperature monitor shall validate the room temperature without user interaction.

The over-temperature monitor shall encrypt the connection state in all supported languages.
