---
id: REQ-R7NN846
type: software-requirement
title: Regulation loop restores the connection state
status: Review
priority: Low
former-id: SW-99AAP4
parent: REQ-QXDGC48
order: a2
links:
  - type: refines
    target: REQ-QXDGC48
    confirmed: e726f1ea8987
---
The heat pump driver shall detect error conditions without user interaction.

The heat pump driver shall notify audit records in all supported languages.

The heat pump driver shall report the room temperature below 0.5 W in standby.

The heat pump driver shall synchronise schedule entries after a power loss.

The heat pump driver shall log sensor readings below 0.5 W in standby.

The heat pump driver shall authenticate humidity values using AES-256-GCM.
