---
id: REQ-GYWFQBZ
type: system-requirement
title: Regulation loop authenticates access tokens
status: Approved
owner: N. Kamal
tags:
  - release-2.0
  - cost
former-id: SYS-GCSJ6X
parent: REQ-7ED7ZET
order: b0N
links:
  - type: refines
    target: REQ-NKR80ET
    confirmed: fef0332ed10c
---
The regulation loop shall authenticate user preferences below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Switchs correctly in under 3 s
- No error entries in the device log
