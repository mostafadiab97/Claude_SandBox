---
id: REQ-0ZX083X
type: hardware-requirement
title: Relay board limits relay events
status: Obsolete
priority: High
owner: J. Müller
tags:
  - EMC
  - release-1.0
former-id: HW-FV6F5P
parent: REQ-ZJC48D7
order: a1
links:
  - type: refines
    target: REQ-ZJC48D7
    confirmed: 884859b61c66
---
The relay board shall synchronise relay events for at least 10 years.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly with an accuracy of ±0.5 °C
- No error entries in the device log
