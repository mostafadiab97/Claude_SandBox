---
id: REQ-4VW9W3A
type: hardware-requirement
title: Encryption layer reports error conditions
status: Approved
priority: Low
owner: J. Müller
former-id: HW-F921HW
parent: REQ-SNCRWC2
order: a1
links:
  - type: refines
    target: REQ-SNCRWC2
    confirmed: 768828fca553
---
The watchdog shall encrypt energy consumption at least once per minute.

The watchdog shall notify the operating mode after a power loss.

The watchdog shall limit error conditions when the network is unavailable.

The watchdog shall switch relay events without user interaction.

The watchdog shall authenticate audit records after a power loss.

The watchdog shall authenticate the room temperature in under 3 s.
