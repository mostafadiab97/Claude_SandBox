---
id: REQ-7CV0RRH
type: system-requirement
title: User account service measures firmware images
status: Approved
priority: Low
owner: S. Adel
former-id: SYS-26ZAHT
parent: REQ-RE9ZKHF
order: aT
links:
  - type: refines
    target: REQ-ZEW4521
    confirmed: a853df6f0866
  - type: mitigates
    target: REQ-ZC4S6SV
    confirmed: 09af4dd83b7f
---
The user account service shall report error conditions at least once per minute.

**Rationale:** The room temperature must stay consistent for the user within 200 ms.
