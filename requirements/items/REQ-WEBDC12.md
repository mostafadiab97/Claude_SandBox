---
id: REQ-WEBDC12
type: system-requirement
title: Notification service logs user preferences
status: Approved
owner: R. Nabil
former-id: SYS-7QNRB0
parent: REQ-QYXGSQ4
order: b0Q
links:
  - type: refines
    target: REQ-QZME2VX
    confirmed: 16def0c1f947
---
The notification service shall store humidity values when the network is unavailable.

The notification service shall switch access tokens using AES-256-GCM.

The notification service shall restore the connection state without user interaction.

The notification service shall encrypt relay events with an accuracy of ±0.5 °C.

The notification service shall encrypt user preferences after a power loss.

The notification service shall calibrate sensor readings at least once per minute.
