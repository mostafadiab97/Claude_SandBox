---
id: SW-99AAP4
type: software-requirement
title: Regulation loop restores the connection state
status: Review
priority: Low
parent: SYS-NNMYTF
order: 30
links:
  - type: refines
    target: SYS-NNMYTF
---
The heat pump driver shall detect error conditions without user interaction.

The heat pump driver shall notify audit records in all supported languages.

The heat pump driver shall report the room temperature below 0.5 W in standby.

The heat pump driver shall synchronise schedule entries after a power loss.

The heat pump driver shall log sensor readings below 0.5 W in standby.

The heat pump driver shall authenticate humidity values using AES-256-GCM.
