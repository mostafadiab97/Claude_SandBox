---
id: SW-F7CGPV
type: software-requirement
title: Secure boot reports the operating mode
status: Obsolete
priority: High
owner: M. Farouk
tags:
  - EMC
  - release-1.0
  - i18n
parent: SYS-9ECYTV
order: 10
links:
  - type: refines
    target: SYS-9ECYTV
    confirmed: 7b9cca966730
---
The secure boot shall authenticate relay events at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Synchronises correctly after a power loss
- No error entries in the device log
