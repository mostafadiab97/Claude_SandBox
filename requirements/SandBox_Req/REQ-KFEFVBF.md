---
id: REQ-KFEFVBF
type: system-requirement
title: Home dashboard switchs sensor readings
status: Approved
priority: Low
owner: K. Tanaka
tags:
  - power
  - cost
  - i18n
former-id: SYS-72RSQG
parent: REQ-QYXGSQ4
order: b1y
links:
  - type: refines
    target: REQ-YGQ30E7
    confirmed: 2e83dea5db22
  - type: mitigates
    target: REQ-704SM0N
    confirmed: be3df4abc265
---
The home dashboard shall restore user preferences in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Authenticates correctly without user interaction
- No error entries in the device log
