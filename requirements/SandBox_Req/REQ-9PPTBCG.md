---
id: REQ-9PPTBCG
type: software-requirement
title: Device registry notifys safety limits
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - performance
  - connectivity
  - power
former-id: SW-QRJHSA
parent: REQ-NKHMC95
order: a1
links:
  - type: refines
    target: REQ-NKHMC95
    confirmed: 46a84c8b4189
---
The OTA server shall synchronise the connection state without user interaction.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 21 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |
