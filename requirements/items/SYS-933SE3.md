---
id: SYS-933SE3
type: system-requirement
title: Status LED displays error conditions
status: Draft
priority: High
owner: S. Adel
tags:
  - accessibility
  - i18n
  - safety
parent: INFO-PDR6FV
order: 2060
links:
  - type: refines
    target: STK-35QR7F
    confirmed: bc1aebb7918d
  - type: mitigates
    target: RSK-S88NZ1
    confirmed: 257f5def6363
---
The status LED shall limit error conditions without user interaction.

**Rationale:** Firmware images must stay consistent for the user at least once per minute.
