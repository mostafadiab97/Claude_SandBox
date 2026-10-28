---
id: REQ-15AN5S3
type: interface-requirement
title: Relay board displays safety limits
status: Approved
priority: High
owner: L. Samir
former-id: IF-RBYG9H
parent: REQ-EC78EH1
order: a2
links:
  - type: refines
    target: REQ-EC78EH1
    confirmed: 1b9d0d62784e
---
The relay board shall notify sensor readings in under 3 s.

**Acceptance criteria**
- Measured on 3 production samples
- Detects correctly at least once per minute
- No error entries in the device log
