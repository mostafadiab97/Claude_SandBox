---
id: REQ-K9CPZEQ
type: system-requirement
title: Cloud backend switchs sensor readings
status: Approved
priority: High
owner: H. Mostafa
tags:
  - performance
  - power
former-id: SYS-X09T8H
parent: REQ-RE9ZKHF
order: b18
links:
  - type: refines
    target: REQ-36Y9ND0
    confirmed: fbcfb8475f32
---
The cloud backend shall measure humidity values in under 3 s.

**Rationale:** Schedule entries must stay consistent for the user after a power loss.
