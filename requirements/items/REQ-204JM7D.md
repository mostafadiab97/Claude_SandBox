---
id: REQ-204JM7D
type: software-requirement
title: Over-temperature monitor synchronises safety limits
status: Draft
priority: Medium
owner: K. Tanaka
tags:
  - release-1.0
  - connectivity
  - cost
former-id: SW-CFWZF1
parent: REQ-MND8W5P
order: a2
links:
  - type: refines
    target: REQ-MND8W5P
    confirmed: 12c71184dbf6
---
The secure boot shall limit the room temperature without user interaction.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 21 | °C |
| Eco | 18 | °C |
| Frost protection | 7 | °C |
