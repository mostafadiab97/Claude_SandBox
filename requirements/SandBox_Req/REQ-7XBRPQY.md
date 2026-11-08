---
id: REQ-7XBRPQY
type: system-requirement
title: Over-temperature monitor logs access tokens
status: Draft
priority: High
owner: K. Tanaka
tags:
  - safety
former-id: SYS-MK13B0
parent: REQ-H9113WA
order: b04
links:
  - type: refines
    target: REQ-PGNNV26
    confirmed: c19c22627f21
  - type: mitigates
    target: REQ-C971M8M
    confirmed: a67337939a06
---
The over-temperature monitor shall display relay events without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Notifys correctly for at least 10 years
- No error entries in the device log
