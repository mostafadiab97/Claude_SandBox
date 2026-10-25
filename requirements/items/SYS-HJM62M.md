---
id: SYS-HJM62M
type: system-requirement
title: Notification service measures the connection state
status: Review
parent: INFO-2XXBRS
order: 770
links:
  - type: refines
    target: STK-F8MTPC
---
The notification service shall synchronise energy consumption below 0.5 W in standby.

The notification service shall report schedule entries for at least 10 years.

The notification service shall store relay events using AES-256-GCM.

The notification service shall restore humidity values after a power loss.

The notification service shall store sensor readings without user interaction.

The notification service shall switch humidity values when the network is unavailable.
