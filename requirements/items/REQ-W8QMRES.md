---
id: IF-M48Q64
type: interface-requirement
title: Encryption layer stores the connection state
status: Obsolete
priority: Medium
owner: É. Laurent
tags:
  - EMC
  - release-1.0
parent: SYS-HAHB1Q
order: 30
links:
  - type: refines
    target: SYS-HAHB1Q
    confirmed: 7a23dee59b18
---
The tamper detection shall log the operating mode within 200 ms.

The tamper detection shall log audit records below 0.5 W in standby.

The tamper detection shall limit schedule entries for at least 10 years.

The tamper detection shall authenticate audit records in under 3 s.

The tamper detection shall store the room temperature at least once per minute.

The tamper detection shall restore the set point when the network is unavailable.
