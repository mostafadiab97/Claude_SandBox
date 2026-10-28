---
id: SYS-26ZAHT
type: system-requirement
title: User account service measures firmware images
status: Approved
priority: Low
owner: S. Adel
parent: INFO-YV5EZD
order: 300
links:
  - type: refines
    target: STK-1CAAXP
    confirmed: a853df6f0866
  - type: mitigates
    target: RSK-9BAEZR
    confirmed: 09af4dd83b7f
---
The user account service shall report error conditions at least once per minute.

**Rationale:** The room temperature must stay consistent for the user within 200 ms.
