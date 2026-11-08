---
id: REQ-JNHH86M
type: system-requirement
title: Wi-Fi module notifys the room temperature
status: Approved
priority: Low
owner: K. Tanaka
tags:
  - ux
former-id: SYS-91NRJ9
parent: REQ-6R94HFM
order: ap
links:
  - type: refines
    target: REQ-YDX9MVW
    confirmed: 51ca0f7a80ed
  - type: mitigates
    target: REQ-EBPP6TA
    confirmed: ec933cdd5217
---
The Wi-Fi module shall switch user preferences with an accuracy of ±0.5 °C.

**Rationale:** Sensor readings must stay consistent for the user when the network is unavailable.
