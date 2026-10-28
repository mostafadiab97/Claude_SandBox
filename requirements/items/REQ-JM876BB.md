---
id: REQ-JM876BB
type: system-requirement
title: Tamper detection switchs access tokens
status: Draft
priority: High
owner: H. Mostafa
tags:
  - power
former-id: SYS-B2CPV7
parent: REQ-H9113WA
order: al
links:
  - type: refines
    target: REQ-N96QXC6
    confirmed: 0b0c08c75491
  - type: mitigates
    target: REQ-C971M8M
    confirmed: a67337939a06
---
The tamper detection shall validate access tokens below 0.5 W in standby.

**Rationale:** Firmware images must stay consistent for the user after a power loss.
