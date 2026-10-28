---
id: REQ-TJ9CZ3B
type: software-requirement
title: Backlight authenticates audit records
status: Approved
priority: Medium
owner: K. Tanaka
former-id: SW-72GHQ2
parent: REQ-22M9B7Z
order: a2
links:
  - type: refines
    target: REQ-22M9B7Z
    confirmed: 407923e760c5
---
The status LED shall encrypt access tokens without user interaction.

**Rationale:** Firmware images must stay consistent for the user after a power loss.
