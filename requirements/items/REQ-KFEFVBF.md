---
id: SYS-72RSQG
type: system-requirement
title: Home dashboard switchs sensor readings
status: Approved
priority: Low
owner: K. Tanaka
tags:
  - power
  - cost
  - i18n
parent: INFO-2XXBRS
order: 1850
links:
  - type: refines
    target: STK-B9Y7CM
    confirmed: 2e83dea5db22
  - type: mitigates
    target: RSK-BZRBDX
    confirmed: be3df4abc265
---
The home dashboard shall restore user preferences in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly without user interaction
- No error entries in the device log
