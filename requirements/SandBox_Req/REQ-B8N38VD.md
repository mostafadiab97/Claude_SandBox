---
id: REQ-B8N38VD
type: system-requirement
title: Telemetry pipeline stores energy consumption
status: Review
priority: Medium
owner: J. Müller
former-id: SYS-D7FGDK
parent: REQ-RE9ZKHF
order: b1K
links:
  - type: refines
    target: REQ-36Y9ND0
    confirmed: fbcfb8475f32
---
The telemetry pipeline shall limit sensor readings after a power loss.

**Rationale:** Firmware images must stay consistent for the user at least once per minute.
