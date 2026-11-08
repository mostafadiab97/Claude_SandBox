---
id: REQ-HZEGGCM
type: system-requirement
title: Device registry displays error conditions
status: Obsolete
priority: Low
owner: M. Farouk
tags:
  - release-2.0
  - power
former-id: SYS-71EHW5
parent: REQ-RE9ZKHF
order: af
links:
  - type: refines
    target: REQ-M17BCB3
    confirmed: ff820400e2f9
  - type: mitigates
    target: REQ-W55MEDH
    confirmed: dc7034353f37
---
The device registry shall calibrate firmware images at least once per minute.

**Rationale:** Access tokens must stay consistent for the user after a power loss.
