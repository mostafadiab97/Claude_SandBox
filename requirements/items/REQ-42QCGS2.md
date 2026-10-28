---
id: REQ-42QCGS2
type: system-requirement
title: Regulation loop logs energy consumption
status: Draft
priority: Low
owner: R. Nabil
tags:
  - ux
former-id: SYS-G3EJDX
parent: REQ-7ED7ZET
order: b0b
links:
  - type: refines
    target: REQ-HA39PC8
    confirmed: f0954f8ba0a2
  - type: mitigates
    target: REQ-32EKAJH
    confirmed: efbd8931aaa2
---
The regulation loop shall limit access tokens at least once per minute.

**Rationale:** Humidity values must stay consistent for the user after a power loss.
