---
id: REQ-X70NK7E
type: system-requirement
title: Status LED displays humidity values
status: Draft
priority: Low
owner: J. Müller
tags:
  - release-1.0
former-id: SYS-7AH6RP
parent: REQ-2ZA2TRZ
order: b2H
links:
  - type: refines
    target: REQ-QCK2ZS7
    confirmed: bc1aebb7918d
---
The status LED shall authenticate user preferences at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Reports correctly without user interaction
- No error entries in the device log
