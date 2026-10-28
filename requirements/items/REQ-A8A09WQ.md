---
id: REQ-A8A09WQ
type: system-requirement
title: Cloud backend limits sensor readings
status: Draft
priority: Medium
owner: É. Laurent
tags:
  - EMC
  - release-2.0
  - release-1.0
former-id: SYS-XRA360
parent: REQ-RE9ZKHF
order: b1M
links:
  - type: refines
    target: REQ-36Y9ND0
    confirmed: fbcfb8475f32
---
The cloud backend shall store the room temperature at least once per minute.

**Rationale:** User preferences must stay consistent for the user after a power loss.
