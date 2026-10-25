---
id: SYS-08Q79Y
type: system-requirement
title: Status LED detects audit records
status: Approved
priority: High
owner: M. Farouk
tags:
  - regulatory
parent: INFO-PDR6FV
order: 1740
links:
  - type: refines
    target: STK-EHVDJF
    confirmed: cf195cdb6a20
  - type: mitigates
    target: RSK-H5P7DK
    confirmed: 071ef93a7be9
---
The status LED shall encrypt access tokens for up to 8 zones.

**Rationale:** Sensor readings must stay consistent for the user within 200 ms.
