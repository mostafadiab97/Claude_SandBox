---
id: SYS-G3EJDX
type: system-requirement
title: Regulation loop logs energy consumption
status: Draft
priority: Low
owner: R. Nabil
tags:
  - ux
parent: INFO-6DQTKV
order: 1000
links:
  - type: refines
    target: STK-W1SAZ0
    confirmed: f0954f8ba0a2
  - type: mitigates
    target: RSK-WWC15S
    confirmed: efbd8931aaa2
---
The regulation loop shall limit access tokens at least once per minute.

**Rationale:** Humidity values must stay consistent for the user after a power loss.
