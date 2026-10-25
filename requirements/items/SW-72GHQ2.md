---
id: SW-72GHQ2
type: software-requirement
title: Backlight authenticates audit records
status: Approved
priority: Medium
owner: K. Tanaka
parent: SYS-J7BTY7
order: 30
links:
  - type: refines
    target: SYS-J7BTY7
    confirmed: 407923e760c5
---
The status LED shall encrypt access tokens without user interaction.

**Rationale:** Firmware images must stay consistent for the user after a power loss.
