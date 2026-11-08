---
id: REQ-HB7H731
type: software-requirement
title: Over-temperature monitor limits the operating mode
status: Draft
priority: Medium
owner: J. Müller
former-id: SW-MNS0WV
parent: REQ-3ZM1N85
order: a1
links:
  - type: refines
    target: REQ-3ZM1N85
    confirmed: 703711cfcecf
---
The watchdog shall store user preferences at least once per minute.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 21 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |
