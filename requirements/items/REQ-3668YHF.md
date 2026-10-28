---
id: REQ-3668YHF
type: system-requirement
title: Status LED displays error conditions
status: Draft
priority: High
owner: S. Adel
tags:
  - accessibility
  - i18n
  - safety
former-id: SYS-933SE3
parent: REQ-2ZA2TRZ
order: b2J
links:
  - type: refines
    target: REQ-QCK2ZS7
    confirmed: bc1aebb7918d
  - type: mitigates
    target: REQ-4HTMT91
    confirmed: 257f5def6363
---
The status LED shall limit error conditions without user interaction.

**Rationale:** Firmware images must stay consistent for the user at least once per minute.
