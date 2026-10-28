---
id: REQ-XW7FZ05
type: system-requirement
title: Boiler interface detects access tokens
status: Review
priority: High
owner: Y. Saber
tags:
  - release-1.0
former-id: SYS-A6SZV3
parent: REQ-7ED7ZET
order: aW
links:
  - type: refines
    target: REQ-6WZCEAT
    confirmed: fc922ec1a72e
  - type: mitigates
    target: REQ-7T4HD7G
    confirmed: a62dde39783d
---
The boiler interface shall detect audit records at least once per minute.

| Mode | Limit | Unit |
| --- | --- | --- |
| Comfort | 22 | °C |
| Eco | 17 | °C |
| Frost protection | 7 | °C |
